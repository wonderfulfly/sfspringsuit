1.  springboot ���N������ƁA�f�[�^�x�[�X�Ɍ����֘A�̃e�[�u�������݂��邩�ǂ����𔻒f���A���݂��Ȃ��ꍇ�́A�����p�̃e�[�u���������I�ɍ쐬�B

2.  sf ��`�𗘗p���Č����ݒ���e�������G�N�X�|�[�g���ASpring Boot �N����Asaasforce�Ɋ��ɓo�^����Ă��郆�[�U�[�Ń��O�C���ł���悤�ɂ���B

3.  ���ʊ֐��݌v���́ASpring Boot �̃f�[�^����R�[�h���쐬�ł��܂��B��{�I��insert�Adelete�Aupdate�Aselect�ł͂Ȃ��A���G��insert select �A�����̃e�[�u����upate�A�����̃e�[�u����delete�A����уT�u�N�G�����܂�select sql�����s����R�[�h�̍쐬�������B

4.  �t�����g�G���h�ƃo�b�N�G���h�̃p�����[�^�擾�́Arequest�̃I�u�W�F�N�g��service�Ɉ����n���Ȃ��A�R���g���[���[�w��reqestMapping�Ńf�[�^���擾���A�f�[�^�͎����I��entity�Ɉ����n���A���̌�̑����entity���g�p���ď�������B .

5.  Validator�͐�p�̃t���[�����[�N spring-boot-starter-validation���̗p�A

6.  �\���� Springboot �� yml �`�����g�p
  yml �`���̍\���t�@�C���ɂ́A���̃����b�g: 
  6.1. �啶���Ə���������ʂ���� 
  6.2. �C���f���g���g�p���ĊK�w�֌W��\�� 
  6.3. �C���f���g�̒����ɐ������Ȃ�
    �v�f�����񂳂�Ă������A�����̗v�f�͓������x�� 4 �ɑ����Ă��邱�Ƃ��Ӗ�����
  6.4. # ���g�p���ăR�����g������

7.  Springboot �ɏ��������W���̋N�����\�b�h�ɕϊ����AMapperScan �A�m�e�[�V�������폜

8.  SpringBoot �� Aspect �A�X�y�N�g���g�p���ă��O���o�͂�������ɕύX
�@Aspect��`�ɏ������郁�\�b�h (�SService �T�t�B�b�N�X�����N���X���̃��\�b�h�Ȃ�) ���G���g�� �|�C���g�Ƃ��č쐬����B
�@�����b�g�́A�n�[�h �R�[�f�B���O���Ȃ��A���Ȍ��ȃR�[�h�A���_��ȕύX�A����ъȒP�Ȋg���B

9.  �g�����U�N�V�����̃��[���o�b�N�𔺂�Ȃ���O�́A�T�[�r�X�w�ŏ�������܂��B Springboot �t���[�����[�N�ɂ���Ē񋟂���� @ControllerAdvice �A�m�e�[�V�������g�p���āA�R���g���[���[ ���C���[�̋@�\�������������邱�ƂŁA�v���W�F�N�g�̂��ׂĂ̏�������X���[���ꂽ��O���L���v�`�����ď������邱�Ƃ��\.

10. �����̃e�[�u�����܂ޓǂݎ��Ə������݂��s���ꍇ�́ASpringboot �̐錾�^�g�����U�N�V���� �A�m�e�[�V�������g�p

11. ���ׂĂ̒P�̃e�X�g�̊�{�N���X�Ƃ��� BaseTest ���쐬����B
�@@RunWith(SpringRunner.class)
�@@SpringBootTest(classes = Application.class) ������ 2 �̒��߂𗘗p

12. Mapper �́AJava �R�[�h�ƕ������A���\�[�X �f�B���N�g���ɌʂɊi�[�B

13. Springboot�{Mybatis��SQL���o�͂Ɋւ���Log4j�̃N���X���g�����āASQL�������Ԃ��o�͂���悤�ɂ���

14. ���O�C�� �C���^�[�Z�v�^�[��ǉ����A���O�C�����K�v�ȃR���g���[���[�������I�ɃC���^�[�Z�v�g����
