<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irG5uId)" class="eog7vzbfp"/><path fill="url(#iyv8I6v)" class="ip5pszche"/><path fill="url(#iKMhfTb)" class="jwr8uz7zj"/><path fill="url(#iR8cN7m)" class="jwr8uz7zj"/><path fill="url(#izaPBzc)" class="hah0-zbnj"/><path fill="url(#iHH4Z2d)" class="hah0-zbnj"/><path fill="url(#iTqwD3c)" class="hah0-zbnj"/><path fill="url(#ipjZckf)" class="hah0-zbnj"/><path fill="url(#i7jFxed)" class="mll-pfbgp"/><path fill="url(#intTCLe)" class="mll-pfbgp"/><path fill="url(#iyTh6rb)" class="mll-pfbgp"/><path fill="url(#iTrtceb)" class="mll-pfbgp"/><path fill="url(#i4ELbPc)" class="o3kvctvem"/><path fill="url(#iKCnxhb)" class="o3kvctvem"/><path fill="url(#iYM70Rb)" class="o3kvctvem"/><path fill="url(#iA1MVHe)" class="o3kvctvem"/><path fill="url(#itdqync)" class="guxuddbqb"/><path fill="url(#isuohDb)" class="guxuddbqb"/><path fill="url(#i7CGo3b)" class="guxuddbqb"/><circle class="ih6qr5bgv"/><circle fill="url(#iQKNmwY)" class="hsrcwsbho"/><circle class="p98cqfpog"/><g filter="url(#ikjg4gd)"><circle stroke="url(#iMoSLYc)" class="wzk8ijn7m"/></g><g filter="url(#iHkCCEa)"><circle class="s9idtdbib"/></g><circle fill="url(#im7L4re)" class="rf_1eg_vz"/><circle fill="url(#ibKpjte)" class="rf_1eg_vz"/><g filter="url(#ih2ezmd)"><path class="i9-n8thlk"/><path fill="url(#iZXYk4b)" class="fve5imhpb"/><path fill="url(#iv0LQrd)" class="fve5imhpb"/><path fill="url(#i1LMXGe)" class="fve5imhpb"/></g><path class="xpmzhr38r"/><path fill="url(#iyN1MLd)" class="vg9iz5chw"/><path fill="url(#iMwDNCO)" class="vg9iz5chw"/><path fill="url(#iCFhbOb)" class="vg9iz5chw"/><path class="qi_rp5b-j"/><path fill="url(#iovMJse)" class="lz_9fdw5m"/><path class="vymo9zb-b"/><g filter="url(#iUgWeGb)"><path class="w3txadbth"/><path fill="url(#iEvw1Ab)" class="gnbpi3qoi"/></g><g filter="url(#iGrCvbc)"><path fill="url(#ihdXkbu)" class="n0uc4q1bj"/></g><path class="lv2_o1b2y"/><path fill="url(#ie0ok1I)" class="urdtwyb4v"/><path class="o2hyzo3kx"/><g filter="url(#iyl5sux)"><path fill="url(#ibKPGwe)" class="df9k09n9o"/></g><path fill="url(#il8yMka)" class="gx4dx6bsq"/><g filter="url(#ijeCjhe)"><ellipse transform="rotate(-27.914 13.564 11.504)" class="h1s2chbac"/><ellipse fill="url(#iPaDKtb)" transform="rotate(-27.914 13.564 11.504)" class="ekg05xlrj"/></g><path class="tiqf49xzb"/><path class="nahwsikny"/><g filter="url(#i5rzNic)"><path stroke="url(#ifnmiub)" class="xbykmf43y"/></g><path class="yjgz689rc"/><g filter="url(#iLOGkGe)"><path stroke="url(#ig4m2Ee)" class="c49yglbmc"/></g><path fill="url(#iUxiRDe)" class="nohgcib5h"/><path fill="url(#i7cvZMb)" class="nohgcib5h"/><path fill="url(#iz582ae)" class="nohgcib5h"/><g filter="url(#iaJncae)"><path class="u3j4bubgl"/><path fill="url(#iaNjJ0d)" class="srgb_ubdm"/><path fill="url(#iT7z1Bc)" class="srgb_ubdm"/></g><g filter="url(#iSbC6Hc)"><path class="nc1hxpk-o"/><path fill="url(#iMfjgAb)" class="nreifgb5f"/><path fill="url(#iro8luK)" class="nreifgb5f"/></g><g filter="url(#iXDOwJc)"><path fill="url(#inwOjye)" class="psjka8bsl"/><path fill="url(#isX13mE)" class="psjka8bsl"/><path fill="url(#if0vhHb)" class="psjka8bsl"/><path fill="url(#i5A9vgd)" class="psjka8bsl"/><path fill="url(#irm3KKb)" class="psjka8bsl"/><path fill="url(#iygnmTc)" class="psjka8bsl"/></g><g filter="url(#i6vMzwe)"><path class="a_4kzmc_h"/><path fill="url(#ipNq5Eb)" class="sd8gombuo"/><path fill="url(#imlzDqi)" class="sd8gombuo"/></g><path fill="url(#iXiZlgc)" class="u-634cczq"/><path fill="url(#iFeJOkd)" class="u-634cczq"/><path fill="url(#iuxOLjb)" class="u-634cczq"/><path fill="url(#iKaahob)" class="u-634cczq"/><path fill="url(#i9AVQfc)" class="pat-1bflm"/><path fill="url(#iFwkiOo)" class="pat-1bflm"/><path fill="url(#ihFA52R)" class="pat-1bflm"/><circle fill="url(#iPFRVXd)" class="r5t-a1weh"/><circle fill="url(#i83LqDd)" class="r5t-a1weh"/><circle fill="url(#iZEZvZb)" class="r5t-a1weh"/><g filter="url(#iNPFlRt)"><circle fill="url(#ig5bXGb)" class="pqwkbhjaq"/></g><g filter="url(#i14Soyd)"><circle class="rau0ebyco"/></g><circle fill="url(#ipALhse)" class="bne_qunkb"/><circle fill="url(#iY3BeEe)" class="bne_qunkb"/><circle fill="url(#i3Tkhvb)" class="bne_qunkb"/><g filter="url(#iA5jkmc)"><circle fill="url(#iW8ovfd)" class="aad6q1qol"/></g><defs><radialGradient id="irG5uId" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.95312 -1.29094 0 10.561 13.633)" gradientUnits="userSpaceOnUse"><stop class="gvv2__18s"/><stop offset="1" class="hmc-s7wiw"/></radialGradient><radialGradient id="iyv8I6v" cx="0" cy="0" r="1" gradientTransform="matrix(-.2233 2.89844 -.93439 -.07199 21.241 13.688)" gradientUnits="userSpaceOnUse"><stop class="a7xlg6yhx"/><stop offset="1" class="fgr5ztbpg"/></radialGradient><radialGradient id="iR8cN7m" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.71875 -11.2218 0 16.007 17.531)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="qd3se0rgm"/><stop offset="1" class="psoka_i3g"/></radialGradient><radialGradient id="izaPBzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9687 8.83796 0 20.976 29.938)" gradientUnits="userSpaceOnUse"><stop class="d6etg3bpc"/><stop offset="1" class="uog-6pbgl"/></radialGradient><radialGradient id="iHH4Z2d" cx="0" cy="0" r="1" gradientTransform="rotate(10.696 -88.26 109.32)scale(2.86223 15.7837)" gradientUnits="userSpaceOnUse"><stop class="map_82oik"/><stop offset="1" class="uqkn5mb7k"/></radialGradient><radialGradient id="iTqwD3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84766 0 0 -9.64948 23.198 24.5)" gradientUnits="userSpaceOnUse"><stop class="l67zujbpu"/><stop offset="1" class="qmocns3dh"/></radialGradient><radialGradient id="i7jFxed" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.90625 -4.9375 0 12.913 22)" gradientUnits="userSpaceOnUse"><stop class="xwh8wibwz"/><stop offset="1" class="siaktr89d"/></radialGradient><radialGradient id="intTCLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.125 -4.52157 0 13.07 18)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="anu_zib6b"/><stop offset="1" class="taq6oxbgc"/></radialGradient><radialGradient id="iyTh6rb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00662 0 0 16.7858 8.796 27.594)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="ly4uss71n"/><stop offset="1" class="qh85l6bny"/></radialGradient><radialGradient id="iTrtceb" cx="0" cy="0" r="1" gradientTransform="matrix(.2461 0 0 20 8.765 29.938)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="d8bqj1ipj"/><stop offset=".952" class="vakzibr9s"/></radialGradient><radialGradient id="i4ELbPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1593 -7.03125 2.71701 -.06156 13.772 29.938)" gradientUnits="userSpaceOnUse"><stop class="s8c_m8bxy"/><stop offset="1" class="wcd2kxb8c"/></radialGradient><radialGradient id="iKCnxhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.29688 -.41239 0 14.51 21.781)" gradientUnits="userSpaceOnUse"><stop class="bxakbpbnw"/><stop offset="1" class="t3whbcbgf"/></radialGradient><radialGradient id="iYM70Rb" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 2.85937 -1.80706 .2518 14.51 18.188)" gradientUnits="userSpaceOnUse"><stop class="tc-f31rjo"/><stop offset="1" class="d2nhlv10m"/></radialGradient><radialGradient id="iA1MVHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45312 -.5039 0 14.51 18.078)" gradientUnits="userSpaceOnUse"><stop class="e56d7dbep"/><stop offset="1" class="zg82anb2t"/></radialGradient><radialGradient id="itdqync" cx="0" cy="0" r="1" gradientTransform="matrix(.1593 -7.03125 2.71701 .06156 18.223 29.938)" gradientUnits="userSpaceOnUse"><stop class="s8c_m8bxy"/><stop offset="1" class="wcd2kxb8c"/></radialGradient><radialGradient id="isuohDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39845 2.85937 -1.1846 -.16507 17.483 18.188)" gradientUnits="userSpaceOnUse"><stop class="al2ofbkms"/><stop offset="1" class="gqq2qjbta"/></radialGradient><radialGradient id="i7CGo3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -.38818 0 18.962 18.094)" gradientUnits="userSpaceOnUse"><stop class="bxakbpbnw"/><stop offset="1" class="t3whbcbgf"/></radialGradient><radialGradient id="iQKNmwY" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69727 0 0 -2.50195 11.314 12.252)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="fv-ihab3v"/><stop offset=".963" class="bjqztpblz"/></radialGradient><radialGradient id="iMoSLYc" cx="0" cy="0" r="1" gradientTransform="rotate(90.994 5.341 16.04)scale(2.85777)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="bytoh5baj"/><stop offset="1" class="r-_dztb_u"/></radialGradient><radialGradient id="im7L4re" cx="0" cy="0" r="1" gradientTransform="rotate(104.287 6.234 14.132)scale(1.29796)" gradientUnits="userSpaceOnUse"><stop class="g_3452bjf"/><stop offset="1" class="smkgpnmwb"/></radialGradient><radialGradient id="ibKpjte" cx="0" cy="0" r="1" gradientTransform="rotate(-50.467 23.568 -15.963)scale(.84075)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="p7g3dw-1h"/><stop offset="1" class="roh0t4blo"/></radialGradient><radialGradient id="iZXYk4b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15626 4.6328 -4.53754 -3.09135 20.85 8.75)" gradientUnits="userSpaceOnUse"><stop class="pot4gabqt"/><stop offset="1" class="p784pabjj"/></radialGradient><radialGradient id="iv0LQrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.70313 -2.69585 0 18.35 11.922)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="u8pt8lv_q"/><stop offset=".514" class="ddscobeqq"/><stop offset="1" class="d7k6qib7z"/></radialGradient><radialGradient id="i1LMXGe" cx="0" cy="0" r="1" gradientTransform="rotate(-130.173 9.796 2.36)scale(1.24739 .86245)" gradientUnits="userSpaceOnUse"><stop class="bqsjubc9v"/><stop offset="1" class="b7gygf5nr"/></radialGradient><radialGradient id="iyN1MLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.75872 .1308 -.5608 -3.25275 16.716 13.035)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="yzq2kjbif"/><stop offset="1" class="e075dnzer"/></radialGradient><radialGradient id="iMwDNCO" cx="0" cy="0" r="1" gradientTransform="rotate(-74.831 16.624 -2.94)scale(2.40856 .31331)" gradientUnits="userSpaceOnUse"><stop class="h8duf1bxd"/><stop offset="1" class="z645iqbrw"/></radialGradient><radialGradient id="iovMJse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04682 .84371 -1.1771 -1.46046 18.53 11.36)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="pwx7w1tsv"/><stop offset="1" class="mra-g7bul"/></radialGradient><radialGradient id="iEvw1Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.974 11.683)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie0ok1I" cx="0" cy="0" r="1" gradientTransform="rotate(141.132 5.078 8.178)scale(1.34457 1.87586)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="pwx7w1tsv"/><stop offset="1" class="mra-g7bul"/></radialGradient><radialGradient id="il8yMka" cx="0" cy="0" r="1" gradientTransform="matrix(.93751 3.07606 -7.97012 2.4291 19.788 4.657)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="ip_2iibnh"/><stop offset=".788" class="nuif9xlfl"/></radialGradient><radialGradient id="iPaDKtb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.592 -.76)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUxiRDe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 -2.10939 2.5359 -5.0342 16.07 5.766)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="fxrx-4bfz"/><stop offset="1" class="brqql5k0f"/></radialGradient><radialGradient id="i7cvZMb" cx="0" cy="0" r="1" gradientTransform="rotate(111.386 7.342 7.975)scale(2.3996 .66997)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="vae8lub_a"/><stop offset="1" class="ienfcucyk"/></radialGradient><radialGradient id="iz582ae" cx="0" cy="0" r="1" gradientTransform="rotate(106.314 5.213 8.76)scale(1.335 1.07537)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="nlravgt3v"/><stop offset="1" class="v42cqkcto"/></radialGradient><radialGradient id="iaNjJ0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.23438 -4.76562 0 18.585 6.922)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="c9i57_blc"/><stop offset="1" class="asi2gqd3l"/></radialGradient><radialGradient id="iT7z1Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.89844 1.1953 -.7833 .58876 20.686 9.687)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="o6mdblbao"/><stop offset="1" class="cc1xhab3r"/></radialGradient><radialGradient id="iMfjgAb" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1 -3.04087 .3326 19.241 3.547)" gradientUnits="userSpaceOnUse"><stop class="ktvc3wz9h"/><stop offset="1" class="y1d9sby0q"/></radialGradient><radialGradient id="iro8luK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46271 -2.01562 2.63403 -1.91149 22.376 5.672)" gradientUnits="userSpaceOnUse"><stop class="z78gnj88j"/><stop offset="1" class="z8hbz1_-a"/></radialGradient><radialGradient id="isX13mE" cx="0" cy="0" r="1" gradientTransform="matrix(2.39062 -1.96875 1.498 1.819 11.085 10.625)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="fu5mseals"/><stop offset="1" class="tk0vr1ber"/></radialGradient><radialGradient id="if0vhHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 2.875 -2.47453 1.50623 15.57 6.719)" gradientUnits="userSpaceOnUse"><stop class="lur1dknhn"/><stop offset="1" class="jhrkx66zx"/></radialGradient><radialGradient id="i5A9vgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59376 1.625 -1.21078 -1.1875 19.226 4.844)" gradientUnits="userSpaceOnUse"><stop class="nrnnc-biv"/><stop offset="1" class="ay6dvtg4c"/></radialGradient><radialGradient id="irm3KKb" cx="0" cy="0" r="1" gradientTransform="matrix(6.84057 -.32813 .32181 6.70902 12.023 5.156)" gradientUnits="userSpaceOnUse"><stop offset=".982" class="e_7vtac5q"/><stop offset=".993" class="y5-px1btw"/></radialGradient><radialGradient id="iygnmTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40626 1.16406 -1.51958 -.53034 15.624 6.547)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="za5enxahd"/><stop offset="1" class="oe-uqrbal"/></radialGradient><radialGradient id="ipNq5Eb" cx="0" cy="0" r="1" gradientTransform="rotate(52.668 1.432 12.977)scale(1.49439 4.8638)" gradientUnits="userSpaceOnUse"><stop class="mqk1vcctk"/><stop offset="1" class="hvho19_je"/></radialGradient><radialGradient id="imlzDqi" cx="0" cy="0" r="1" gradientTransform="matrix(4.1875 -1.25145 .54354 1.81875 10.163 6.658)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="u6ggrwbro"/><stop offset="1" class="cv2bxebia"/></radialGradient><radialGradient id="iXiZlgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.25 3.82218 0 8.796 29.938)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="qo5hjkb1l"/><stop offset=".918" class="rnd-2g3zm"/></radialGradient><radialGradient id="iFeJOkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84375 0 0 -11.0312 8.632 29.938)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="xw_ma5b4i"/><stop offset="1" class="bzngqmzdt"/></radialGradient><radialGradient id="iuxOLjb" cx="0" cy="0" r="1" gradientTransform="rotate(107.068 -2.792 12.98)scale(3.96604 2.57642)" gradientUnits="userSpaceOnUse"><stop class="z-39yxbny"/><stop offset="1" class="n1fah1bul"/></radialGradient><radialGradient id="iKaahob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.57812 .20957 0 8.602 29.938)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="im-luab0p"/><stop offset="1" class="mc5wqkbfu"/></radialGradient><radialGradient id="i9AVQfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4958 2.84375 0 24.163 29.938)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="avhg4lb0o"/><stop offset=".968" class="jsgqqxbkh"/></radialGradient><radialGradient id="iFwkiOo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.375 1.1122 0 23.198 29.938)" gradientUnits="userSpaceOnUse"><stop class="p1vewccqc"/><stop offset="1" class="aqq8mk3_r"/></radialGradient><radialGradient id="iPFRVXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5781 2.46876 -2.36914 -1.51443 17.023 4.938)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="yem538otj"/><stop offset="1" class="h33d0vgtb"/></radialGradient><radialGradient id="i83LqDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.10938 -2.33691 0 15.997 5.656)" gradientUnits="userSpaceOnUse"><stop offset=".785" class="joaz6acnx"/><stop offset="1" class="vno_7t63q"/></radialGradient><radialGradient id="iZEZvZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33397 .75978 -1.02369 -1.79734 15.997 6.146)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="aj22pcbyb"/><stop offset="1" class="wz6bzjb_t"/></radialGradient><radialGradient id="ig5bXGb" cx="0" cy="0" r="1" gradientTransform="rotate(122.588 7.022 7.182)scale(2.45266 2.35369)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="iv7gqubaa"/><stop offset="1" class="vg6jezb7s"/></radialGradient><radialGradient id="ipALhse" cx="0" cy="0" r="1" gradientTransform="rotate(133.112 6.962 6.472)scale(1.00596)" gradientUnits="userSpaceOnUse"><stop class="x2nz94bxt"/><stop offset="1" class="pl3efkh-l"/></radialGradient><radialGradient id="iY3BeEe" cx="0" cy="0" r="1" gradientTransform="rotate(-82.06 11.947 -5.64)scale(.83417 1.47066)" gradientUnits="userSpaceOnUse"><stop class="sof8zwbsb"/><stop offset="1" class="cwth_ve7b"/></radialGradient><radialGradient id="i3Tkhvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7871 .29102 -.40497 -1.0953 15.997 6.146)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="wci1pqi0w"/><stop offset="1" class="d6o1iwbzc"/></radialGradient><filter id="ikjg4gd" width="3.377" height="3.377" x="18.992" y="10.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".1"/></filter><filter id="iHkCCEa" width="1.99" height="1.99" x="10.155" y="11.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".1"/></filter><filter id="ih2ezmd" width="11.59" height="10.869" x="10.786" y="8.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.803922 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2281"/></filter><filter id="iUgWeGb" width=".787" height=".697" x="17.468" y="11.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".05"/></filter><filter id="iGrCvbc" width=".892" height=".914" x="18.308" y="11.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".1"/></filter><filter id="iyl5sux" width=".987" height="1.041" x="13.862" y="11.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".1"/></filter><filter id="ijeCjhe" width=".914" height=".705" x="13.107" y="11.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".05"/></filter><filter id="i5rzNic" width="2.127" height=".809" x="12.303" y="9.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".075"/></filter><filter id="iLOGkGe" width="2.127" height=".809" x="17.6" y="9.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".075"/></filter><filter id="iaJncae" width="6.421" height="3.705" x="15.673" y="7.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.4 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2281"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.298039 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2281" result="effect2_innerShadow_2_2281"/></filter><filter id="iSbC6Hc" width="3.614" height="2.832" x="18.762" y="3.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.396078 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2281"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.156863 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2281" result="effect2_innerShadow_2_2281"/></filter><filter id="iXDOwJc" width="9.089" height="6.986" x="9.874" y="3.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.160784 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2281"/></filter><filter id="i6vMzwe" width="5.734" height="3.102" x="9.782" y="3.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.113725 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2281"/></filter><filter id="iNPFlRt" width="2.688" height="2.688" x="14.653" y="4.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".05"/></filter><filter id="i14Soyd" width="1.852" height="1.852" x="14.997" y="5.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".05"/></filter><filter id="iA5jkmc" width="1.329" height="1.329" x="15.333" y="5.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2281" stdDeviation=".05"/></filter><linearGradient id="iKMhfTb" x1="16.007" x2="16.007" y1="16.766" y2="29.938" gradientUnits="userSpaceOnUse"><stop offset=".665" class="c78jw65ce"/><stop offset="1" class="yqin9d1eu"/></linearGradient><linearGradient id="ipjZckf" x1="23.198" x2="23.066" y1="26.895" y2="26.895" gradientUnits="userSpaceOnUse"><stop class="tw_ou6-wu"/><stop offset="1" class="woyxclbuf"/></linearGradient><linearGradient id="iCFhbOb" x1="16.21" x2="16.21" y1="14.328" y2="13.628" gradientUnits="userSpaceOnUse"><stop offset=".123" class="g8hsjbmmz"/><stop offset="1" class="i7wpi6bfc"/></linearGradient><linearGradient id="ihdXkbu" x1="18.942" x2="18.685" y1="11.661" y2="11.826" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibKPGwe" x1="14.579" x2="14.265" y1="11.653" y2="11.847" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifnmiub" x1="14.23" x2="12.265" y1="9.399" y2="10.031" gradientUnits="userSpaceOnUse"><stop class="nug-ljdth"/><stop offset="1" class="tjw25wbog"/></linearGradient><linearGradient id="ig4m2Ee" x1="19.601" x2="17.8" y1="9.809" y2="9.399" gradientUnits="userSpaceOnUse"><stop class="isnhr_blk"/><stop offset="1" class="o4v5v5src"/></linearGradient><linearGradient id="inwOjye" x1="18.038" x2="10.132" y1="4.938" y2="10.542" gradientUnits="userSpaceOnUse"><stop class="xiq09ubck"/><stop offset="1" class="z1vah_bkx"/></linearGradient><linearGradient id="ihFA52R" x1="25.57" x2="27.007" y1="30.344" y2="25.25" gradientUnits="userSpaceOnUse"><stop class="bda624niz"/><stop offset="1" class="v8mqcsb1j"/></linearGradient><linearGradient id="iW8ovfd" x1="15.997" x2="15.997" y1="5.859" y2="6.711" gradientUnits="userSpaceOnUse"><stop class="pln90ra2q"/><stop offset="1" class="v3r7tab1y"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-genie" /></template>
<style>
.a_4kzmc_h {
  fill: var(--svg-color--f1252d, #F1252D);
  d: path("M9.782 6.658c.267-.297.773-.73 1.248-.916c.809-.265 2.489-.457 3.965-.508c.248-.11.615-.582.5-1.578h-2.707c-1.713.019-2.861.898-3.006 3.002");
}

.a7xlg6yhx {
  stop-color: var(--svg-color--3c3a3b, #3C3A3B);
}

.aad6q1qol {
  cx: 15.997px;
  cy: 6.146px;
  r: 0.564px;
}

.aj22pcbyb {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
  stop-opacity: 0;
}

.al2ofbkms {
  stop-color: var(--svg-color--99943c, #99943C);
}

.anu_zib6b {
  stop-color: var(--svg-color--952238, #952238);
}

.aqq8mk3_r {
  stop-color: var(--svg-color--3cc2ff, #3CC2FF);
  stop-opacity: 0;
}

.asi2gqd3l {
  stop-color: var(--svg-color--ff5875, #FF5875);
  stop-opacity: 0;
}

.avhg4lb0o {
  stop-color: var(--svg-color--63e0ff, #63E0FF);
}

.ay6dvtg4c {
  stop-color: var(--svg-color--ff636d, #FF636D);
  stop-opacity: 0;
}

.b7gygf5nr {
  stop-color: var(--svg-color--63c4ff, #63C4FF);
  stop-opacity: 0;
}

.bda624niz {
  stop-color: var(--svg-color--56cdff, #56CDFF);
}

.bjqztpblz {
  stop-color: var(--svg-color--71c3ff, #71C3FF);
}

.bne_qunkb {
  cx: 15.997px;
  cy: 6.146px;
  r: 0.826px;
}

.bqsjubc9v {
  stop-color: var(--svg-color--63c4ff, #63C4FF);
}

.brqql5k0f {
  stop-color: var(--svg-color--ff6b79, #FF6B79);
}

.bxakbpbnw {
  stop-color: var(--svg-color--fedd3a, #FEDD3A);
}

.bytoh5baj {
  stop-color: var(--svg-color--5ac0ff, #5AC0FF);
}

.bzngqmzdt {
  stop-color: var(--svg-color--62bceb, #62BCEB);
}

.c49yglbmc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.527 9.809c-.238-.157-.77-.508-1.727-.383");
}

.c78jw65ce {
  stop-color: var(--svg-color--42c2ff, #42C2FF);
}

.c9i57_blc {
  stop-color: var(--svg-color--ff5875, #FF5875);
}

.cc1xhab3r {
  stop-color: var(--svg-color--8c4277, #8C4277);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv2bxebia {
  stop-color: var(--svg-color--fd6772, #FD6772);
  stop-opacity: 0;
}

.cwth_ve7b {
  stop-color: var(--svg-color--e21a67, #E21A67);
  stop-opacity: 0;
}

.d2nhlv10m {
  stop-color: var(--svg-color--9a9338, #9A9338);
  stop-opacity: 0;
}

.d6etg3bpc {
  stop-color: var(--svg-color--ff4472, #FF4472);
}

.d6o1iwbzc {
  stop-color: var(--svg-color--f8606c, #F8606C);
}

.d7k6qib7z {
  stop-color: var(--svg-color--4ed2ff, #4ED2FF);
  stop-opacity: 0;
}

.d8bqj1ipj {
  stop-color: var(--svg-color--b6396a, #B6396A);
}

.ddscobeqq {
  stop-color: var(--svg-color--61d3ff, #61D3FF);
}

.df9k09n9o {
  d: path("M14.649 11.91c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.e_7vtac5q {
  stop-color: var(--svg-color--ff5b5e, #FF5B5E);
  stop-opacity: 0;
}

.e075dnzer {
  stop-color: var(--svg-color--68d2ff, #68D2FF);
  stop-opacity: 0;
}

.e56d7dbep {
  stop-color: var(--svg-color--7c7e3d, #7C7E3D);
}

.ekg05xlrj {
  cx: 13.564px;
  cy: 11.504px;
  rx: 0.39px;
  ry: 0.197px;
}

.eog7vzbfp {
  d: path("M10.288 13.383h1.562v3.203c-.286-.162-.898-.526-1.242-1.082c-.32-.477-.32-1.687-.32-2.121");
}

.fgr5ztbpg {
  stop-color: var(--svg-color--352739, #352739);
}

.ft5dv1b6b {
  fill: none;
}

.fu5mseals {
  stop-color: var(--svg-color--cb2c70, #CB2C70);
}

.fv-ihab3v {
  stop-color: var(--svg-color--33adf7, #33ADF7);
  stop-opacity: 0;
}

.fve5imhpb {
  d: path("m10.786 8.073l.295 6.523c.026.499.23 1.705.84 2.537c.761 1.04 2.27 1.56 3.155 1.56h2.01c.886 0 2.394-.52 3.155-1.56c.61-.832.814-2.038.84-2.537l.295-6.523z");
}

.fxrx-4bfz {
  stop-color: var(--svg-color--fc2b32, #FC2B32);
}

.g_3452bjf {
  stop-color: var(--svg-color--4abaff, #4ABAFF);
}

.g8hsjbmmz {
  stop-color: var(--svg-color--30b0ff, #30B0FF);
}

.gnbpi3qoi {
  d: path("M18.139 11.31c.063.086-.07.19-.22.303c-.152.113-.264.192-.328.107s.007-.245.159-.359c.15-.113.325-.135.389-.05");
}

.gqq2qjbta {
  stop-color: var(--svg-color--cabb36, #CABB36);
  stop-opacity: 0;
}

.guxuddbqb {
  d: path("M18.962 29.938V17.149q-.72-.196-1.479-.294v13.083z");
}

.gvv2__18s {
  stop-color: var(--svg-color--4f4e4f, #4F4E4F);
}

.gx4dx6bsq {
  d: path("M22.374 6.27c-1.008-1.187-3.186-1.436-4.086-1.286L16.21 6.141l-.403 2.304h3.81c.573 0 .993.216 1.23.508c.403.436.443.9.426 1.32a6 6 0 0 0-.007.247c.175-.086.302-.185.42-.348c.522-.714.6-1.772.696-3.344q.018-.29-.008-.559");
}

.h1s2chbac {
  cx: 13.564px;
  cy: 11.504px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.h33d0vgtb {
  stop-color: var(--svg-color--e57241, #E57241);
}

.h8duf1bxd {
  stop-color: var(--svg-color--5ec2ff, #5EC2FF);
}

.hah0-zbnj {
  d: path("M23.198 19.442v10.496h-5.715V16.864a10.96 10.96 0 0 1 5.715 2.578");
}

.hmc-s7wiw {
  stop-color: var(--svg-color--322035, #322035);
}

.hsrcwsbho {
  cx: 11.314px;
  cy: 12.252px;
  r: 1.697px;
}

.hvho19_je {
  stop-color: var(--svg-color--da5d60, #DA5D60);
  stop-opacity: 0;
}

.i7wpi6bfc {
  stop-color: var(--svg-color--30b0ff, #30B0FF);
  stop-opacity: 0;
}

.i9-n8thlk {
  fill: var(--svg-color--3db3ff, #3DB3FF);
  d: path("m10.786 8.073l.295 6.523c.026.499.23 1.705.84 2.537c.761 1.04 2.27 1.56 3.155 1.56h2.01c.886 0 2.394-.52 3.155-1.56c.61-.832.814-2.038.84-2.537l.295-6.523z");
}

.ienfcucyk {
  stop-color: var(--svg-color--ff5458, #FF5458);
  stop-opacity: 0;
}

.ih6qr5bgv {
  cx: 11.314px;
  cy: 12.252px;
  r: 1.697px;
  fill: var(--svg-color--2eaaf2, #2EAAF2);
}

.im-luab0p {
  stop-color: var(--svg-color--5bc5ff, #5BC5FF);
}

.ip_2iibnh {
  stop-color: var(--svg-color--ff666e, #FF666E);
}

.ip5pszche {
  d: path("M21.8 13.383h-1.563v3.203c.286-.162.898-.526 1.242-1.082c.32-.477.32-1.687.32-2.121");
}

.isnhr_blk {
  stop-color: var(--svg-color--50494c, #50494C);
}

.iv7gqubaa {
  stop-color: var(--svg-color--ffb53f, #FFB53F);
}

.jhrkx66zx {
  stop-color: var(--svg-color--e51d5e, #E51D5E);
  stop-opacity: 0;
}

.joaz6acnx {
  stop-color: var(--svg-color--cf634e, #CF634E);
  stop-opacity: 0;
}

.jsgqqxbkh {
  stop-color: var(--svg-color--57cfff, #57CFFF);
}

.jwr8uz7zj {
  d: path("M5.007 27.766c0-6.075 4.925-11 11-11s11 4.925 11 11v2.172h-22z");
}

.ktvc3wz9h {
  stop-color: var(--svg-color--df6b6d, #DF6B6D);
}

.l67zujbpu {
  stop-color: var(--svg-color--ff636e, #FF636E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lur1dknhn {
  stop-color: var(--svg-color--e51d5e, #E51D5E);
}

.lv2_o1b2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.626 10.85c-.653 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.ly4uss71n {
  stop-color: var(--svg-color--f15172, #F15172);
}

.lz_9fdw5m {
  d: path("M18.204 11.122a.893.893 0 0 1 .861 1.129H17.34a.897.897 0 0 1 .865-1.129");
}

.map_82oik {
  stop-color: var(--svg-color--d61e37, #D61E37);
}

.mc5wqkbfu {
  stop-color: var(--svg-color--5bc5ff, #5BC5FF);
  stop-opacity: 0;
}

.mll-pfbgp {
  d: path("M14.51 16.867v13.07H8.797V19.46a10.96 10.96 0 0 1 5.715-2.593");
}

.mqk1vcctk {
  stop-color: var(--svg-color--da5d60, #DA5D60);
}

.mra-g7bul {
  stop-color: var(--svg-color--7c544c, #7C544C);
}

.n0uc4q1bj {
  d: path("M19 11.898a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.n1fah1bul {
  stop-color: var(--svg-color--5bb9ea, #5BB9EA);
  stop-opacity: 0;
}

.nahwsikny {
  stroke: var(--svg-color--271218, #271218);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.503 9.809c.237-.157.77-.508 1.727-.383");
}

.nc1hxpk-o {
  fill: var(--svg-color--ff4449, #FF4449);
  d: path("M18.857 4.945c1.05.003 2.684.343 3.517 1.324l.002.02c-.145-1.632-1.44-2.615-3.055-2.633h-.56c.078.374.118.82.096 1.29");
}

.nlravgt3v {
  stop-color: var(--svg-color--cf3142, #CF3142);
}

.nohgcib5h {
  d: path("M18.762 3.656h-5.974c-1.758.02-2.922.946-3.015 3.172c.05.827.153 2.086.28 2.527c.14.484.463.854.848 1.192c0-.324-.056-.902.107-1.26a1.48 1.48 0 0 1 1.366-.842h4.04c2.398-.773 2.648-3.328 2.348-4.789");
}

.nreifgb5f {
  d: path("M18.857 4.945c1.05.003 2.684.343 3.517 1.324l.002.02c-.145-1.632-1.44-2.615-3.055-2.633h-.56c.078.374.118.82.096 1.29");
}

.nrnnc-biv {
  stop-color: var(--svg-color--ff636d, #FF636D);
}

.nug-ljdth {
  stop-color: var(--svg-color--4a4346, #4A4346);
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o2hyzo3kx {
  fill: var(--svg-color--000, #000);
  d: path("M14.345 12.015a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.236");
}

.o3kvctvem {
  d: path("M13.033 29.938V17.149q.721-.196 1.478-.294v13.083z");
}

.o4v5v5src {
  stop-color: var(--svg-color--50494c, #50494C);
  stop-opacity: 0;
}

.o6mdblbao {
  stop-color: var(--svg-color--8c4277, #8C4277);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe-uqrbal {
  stop-color: var(--svg-color--cf344c, #CF344C);
  stop-opacity: 0;
}

.p1vewccqc {
  stop-color: var(--svg-color--3cc2ff, #3CC2FF);
}

.p784pabjj {
  stop-color: var(--svg-color--4cc6ff, #4CC6FF);
  stop-opacity: 0;
}

.p7g3dw-1h {
  stop-color: var(--svg-color--57beff, #57BEFF);
  stop-opacity: 0;
}

.p98cqfpog {
  cx: 20.681px;
  cy: 12.252px;
  r: 1.697px;
  fill: var(--svg-color--18b4ff, #18B4FF);
}

.pat-1bflm {
  d: path("M23.198 29.938V19.441a10.98 10.98 0 0 1 3.809 8.324v2.172z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl3efkh-l {
  stop-color: var(--svg-color--e92b2e, #E92B2E);
}

.pln90ra2q {
  stop-color: var(--svg-color--f43243, #F43243);
}

.pot4gabqt {
  stop-color: var(--svg-color--4cc6ff, #4CC6FF);
}

.pqwkbhjaq {
  cx: 15.997px;
  cy: 6.146px;
  r: 1.244px;
}

.psjka8bsl {
  d: path("M15.67 6.844c1.393-.846 1.555-2.411 1.454-3.188h1.638c.28 1.366.08 3.69-1.908 4.617c-.283.133-.599.172-.911.172h-3.57q-.091 0-.178.01a1.47 1.47 0 0 0-1.188.833c-.134.293-.123.73-.114 1.057l.003.197c-.383-.336-.703-.706-.842-1.187c-.069-.236-.13-.707-.18-1.221a5 5 0 0 1 .772-.603c.807-.543 2.47-.705 3.172-.687z");
}

.psoka_i3g {
  stop-color: var(--svg-color--0f8dff, #0F8DFF);
  stop-opacity: 0;
}

.pwx7w1tsv {
  stop-color: var(--svg-color--865f52, #865F52);
}

.qd3se0rgm {
  stop-color: var(--svg-color--0f8dff, #0F8DFF);
}

.qh85l6bny {
  stop-color: var(--svg-color--f05163, #F05163);
  stop-opacity: 0;
}

.qi_rp5b-j {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.411 10.85c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.qmocns3dh {
  stop-color: var(--svg-color--ff636e, #FF636E);
  stop-opacity: 0;
}

.qo5hjkb1l {
  stop-color: var(--svg-color--39beff, #39BEFF);
}

.r-_dztb_u {
  stop-color: var(--svg-color--5ac0ff, #5AC0FF);
  stop-opacity: 0;
}

.r5t-a1weh {
  cx: 15.997px;
  cy: 6.146px;
  r: 1.486px;
}

.rau0ebyco {
  cx: 15.923px;
  cy: 6.217px;
  r: 0.826px;
  fill: var(--svg-color--df6631, #DF6631);
}

.rf_1eg_vz {
  cx: 20.814px;
  cy: 12.252px;
  r: 0.795px;
}

.rnd-2g3zm {
  stop-color: var(--svg-color--75d9ff, #75D9FF);
}

.roh0t4blo {
  stop-color: var(--svg-color--57beff, #57BEFF);
}

.s8c_m8bxy {
  stop-color: var(--svg-color--ff9a38, #FF9A38);
}

.s9idtdbib {
  cx: 11.149px;
  cy: 12.252px;
  r: 0.795px;
  fill: var(--svg-color--2ea9f4, #2EA9F4);
}

.sd8gombuo {
  d: path("M9.782 6.658c.267-.297.773-.73 1.248-.916c.809-.265 2.489-.457 3.965-.508c.248-.11.615-.582.5-1.578h-2.707c-1.713.019-2.861.898-3.006 3.002");
}

.siaktr89d {
  stop-color: var(--svg-color--fc2c61, #FC2C61);
}

.smkgpnmwb {
  stop-color: var(--svg-color--3db5ff, #3DB5FF);
}

.sof8zwbsb {
  stop-color: var(--svg-color--e21a67, #E21A67);
}

.srgb_ubdm {
  d: path("M21.988 9.605c.03-.456-.044-.935-.317-1.352c-.614-.939-2.273-1.139-2.781-1.139h-1.258l-1.809 1.331h3.793c.574 0 .994.216 1.23.508c.404.436.44.9.422 1.32a6 6 0 0 0-.007.247c.184-.09.307-.185.426-.348a2.4 2.4 0 0 0 .301-.567");
}

.t3whbcbgf {
  stop-color: var(--svg-color--fedd3a, #FEDD3A);
  stop-opacity: 0;
}

.taq6oxbgc {
  stop-color: var(--svg-color--da2730, #DA2730);
  stop-opacity: 0;
}

.tc-f31rjo {
  stop-color: var(--svg-color--747741, #747741);
}

.tiqf49xzb {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16 15.399c-.556 0-1.075-.199-1.411-.344c-.173-.075-.289.096-.213.242c.208.4.703.86 1.624.86c.914 0 1.435-.479 1.67-.902c.068-.12-.07-.278-.253-.169a3.4 3.4 0 0 1-1.417.313");
}

.tjw25wbog {
  stop-color: var(--svg-color--4a4346, #4A4346);
  stop-opacity: 0;
}

.tk0vr1ber {
  stop-color: var(--svg-color--cb2c70, #CB2C70);
  stop-opacity: 0;
}

.tw_ou6-wu {
  stop-color: var(--svg-color--f83c69, #F83C69);
}

.u-634cczq {
  d: path("M8.796 19.459v10.479H5.007v-2.172c0-3.317 1.468-6.29 3.789-8.307");
}

.u3j4bubgl {
  fill: var(--svg-color--ff3565, #FF3565);
  d: path("M21.988 9.605c.03-.456-.044-.935-.317-1.352c-.614-.939-2.273-1.139-2.781-1.139h-1.258l-1.809 1.331h3.793c.574 0 .994.216 1.23.508c.404.436.44.9.422 1.32a6 6 0 0 0-.007.247c.184-.09.307-.185.426-.348a2.4 2.4 0 0 0 .301-.567");
}

.u6ggrwbro {
  stop-color: var(--svg-color--fd6772, #FD6772);
}

.u8pt8lv_q {
  stop-color: var(--svg-color--4bd1ff, #4BD1FF);
}

.uog-6pbgl {
  stop-color: var(--svg-color--f63b44, #F63B44);
}

.uqkn5mb7k {
  stop-color: var(--svg-color--f93e4d, #F93E4D);
  stop-opacity: 0;
}

.urdtwyb4v {
  d: path("M13.833 11.122a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.v3r7tab1y {
  stop-color: var(--svg-color--fc3364, #FC3364);
}

.v42cqkcto {
  stop-color: var(--svg-color--cf3142, #CF3142);
  stop-opacity: 0;
}

.v8mqcsb1j {
  stop-color: var(--svg-color--56cdff, #56CDFF);
  stop-opacity: 0;
}

.vae8lub_a {
  stop-color: var(--svg-color--ff5458, #FF5458);
}

.vakzibr9s {
  stop-color: var(--svg-color--e24371, #E24371);
  stop-opacity: 0;
}

.vg6jezb7s {
  stop-color: var(--svg-color--ff8c3f, #FF8C3F);
}

.vg9iz5chw {
  d: path("m15.62 11.845l-.48 1.811c-.109.365.1.672.47.672h.786c.37 0 .602-.34.494-.7l-.532-1.783c-.113-.393-.618-.393-.738 0");
}

.vno_7t63q {
  stop-color: var(--svg-color--cf634e, #CF634E);
}

.vymo9zb-b {
  fill: var(--svg-color--000, #000);
  d: path("M17.693 12.015a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.w3txadbth {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M18.139 11.31c.063.086-.07.19-.22.303c-.152.113-.264.192-.328.107s.007-.245.159-.359c.15-.113.325-.135.389-.05");
}

.wcd2kxb8c {
  stop-color: var(--svg-color--fad43b, #FAD43B);
}

.wci1pqi0w {
  stop-color: var(--svg-color--f8606c, #F8606C);
  stop-opacity: 0;
}

.woyxclbuf {
  stop-color: var(--svg-color--f83c69, #F83C69);
  stop-opacity: 0;
}

.wz6bzjb_t {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
}

.wzk8ijn7m {
  cx: 20.681px;
  cy: 12.252px;
  r: 1.389px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.x2nz94bxt {
  stop-color: var(--svg-color--ff5c61, #FF5C61);
}

.xbykmf43y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.503 9.809c.237-.157.77-.508 1.727-.383");
}

.xiq09ubck {
  stop-color: var(--svg-color--ff363d, #FF363D);
}

.xpmzhr38r {
  fill: var(--svg-color--35beff, #35BEFF);
  d: path("m15.62 11.845l-.48 1.811c-.109.365.1.672.47.672h.786c.37 0 .602-.34.494-.7l-.532-1.783c-.113-.393-.618-.393-.738 0");
}

.xw_ma5b4i {
  stop-color: var(--svg-color--62bceb, #62BCEB);
  stop-opacity: 0;
}

.xwh8wibwz {
  stop-color: var(--svg-color--f02c36, #F02C36);
}

.y1d9sby0q {
  stop-color: var(--svg-color--df6b6d, #DF6B6D);
  stop-opacity: 0;
}

.y5-px1btw {
  stop-color: var(--svg-color--ff5b5e, #FF5B5E);
}

.yem538otj {
  stop-color: var(--svg-color--ffdd4f, #FFDD4F);
}

.yjgz689rc {
  stroke: var(--svg-color--271218, #271218);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.527 9.809c-.238-.157-.77-.508-1.727-.383");
}

.yqin9d1eu {
  stop-color: var(--svg-color--41c0ff, #41C0FF);
}

.yzq2kjbif {
  stop-color: var(--svg-color--68d2ff, #68D2FF);
}

.z-39yxbny {
  stop-color: var(--svg-color--5bb9ea, #5BB9EA);
}

.z1vah_bkx {
  stop-color: var(--svg-color--ff6d85, #FF6D85);
}

.z645iqbrw {
  stop-color: var(--svg-color--5ec2ff, #5EC2FF);
  stop-opacity: 0;
}

.z78gnj88j {
  stop-color: var(--svg-color--ff5b66, #FF5B66);
}

.z8hbz1_-a {
  stop-color: var(--svg-color--ff5b66, #FF5B66);
  stop-opacity: 0;
}

.za5enxahd {
  stop-color: var(--svg-color--cf344c, #CF344C);
}

.zg82anb2t {
  stop-color: var(--svg-color--b4a43e, #B4A43E);
  stop-opacity: 0;
}

</style>
