<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKEe48b)"><path fill="url(#iZ2w8Cc)" class="bscxqsbmf"/><path fill="url(#iyrOtsd)" class="bscxqsbmf"/><path fill="url(#i7oZiJb)" class="bscxqsbmf"/><path fill="url(#igvRrqe)" class="bscxqsbmf"/></g><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#ilzofLk)"><path class="xk18tyb3e"/></g><path class="duc38e2qw"/><path fill="url(#iCoINWb)" class="zqss5obsp"/><path fill="url(#i6jO4ud)" class="zqss5obsp"/><path fill="url(#iwtLm3r)" class="zqss5obsp"/><path fill="url(#iRlvw5c)" class="zqss5obsp"/><path class="fgv70eb9t"/><path fill="url(#iw5yIye)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i8g26lb)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><g filter="url(#iPg2QYb)"><path fill="url(#iblgbvb)" class="dvr2s59yl"/></g><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#iXfr0He)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#ieBCGYb)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iDAYawb)"><path fill="url(#iQbAUIc)" class="z84sqrd2n"/></g><g filter="url(#iOPhxBc)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#iBdq6Yd)"><path class="z5g21op2e"/></g><g filter="url(#iDk0IXI)"><path fill="url(#iEYHwqd)" class="pv8cx5b7o"/><path fill="url(#ibrdWNd)" class="pv8cx5b7o"/><path fill="url(#i024Txd)" class="pv8cx5b7o"/><path fill="url(#ieWdNxd)" class="pv8cx5b7o"/><path fill="url(#iqGuoib)" class="pv8cx5b7o"/></g><g filter="url(#iBlKgXc)"><path stroke="url(#iYEUgQc)" class="waqwqw1tk"/></g><g filter="url(#i654bKc)"><path stroke="url(#i5g22Rd)" class="phyw90buy"/></g><g filter="url(#iX7iUyc)"><path stroke="url(#iYxUmRb)" class="vz0qjzgsj"/></g><path fill="url(#i51UrPe)" class="b73qugbel"/><path fill="url(#iE1PSBb)" class="b73qugbel"/><path fill="url(#iZ8UhGy)" class="b73qugbel"/><path fill="url(#i6Qchqd)" class="fjwq502mo"/><path fill="url(#iCKaJkb)" class="fjwq502mo"/><g filter="url(#iHWLdxc)"><path class="cuk6lqbzk"/></g><g filter="url(#iA0FRwc)"><path class="zuj_hmbed"/></g><g filter="url(#ie6VMXd)"><path fill="url(#ii5z7uc)" class="r0-_ekb3n"/><path fill="url(#iyT4fsd)" class="r0-_ekb3n"/><path fill="url(#ix0VL4c)" class="r0-_ekb3n"/><path fill="url(#i8ycffu)" class="r0-_ekb3n"/><path fill="url(#iMWT1Dc)" class="r0-_ekb3n"/><path fill="url(#isLW6ME)" class="r0-_ekb3n"/><path fill="url(#iMniqYd)" class="r0-_ekb3n"/></g><path fill="url(#iVE67xc)" class="r0-_ekb3n"/><path fill="url(#ihRY7vd)" class="r0-_ekb3n"/><g filter="url(#ikFc29c)"><path class="rg9aui68e"/></g><g filter="url(#iULXJYb)"><path fill="url(#iZn0Whb)" class="builfkb8w"/><path fill="url(#iVedWob)" class="builfkb8w"/><path fill="url(#ibACQQb)" class="builfkb8w"/><path fill="url(#ioyX2Cb)" class="builfkb8w"/></g><g filter="url(#i0M7Wyx)"><path stroke="url(#i5NVrab)" class="f3w949b_d"/></g><path fill="url(#ibFO5je)" class="hxqcnhbrq"/><g filter="url(#iEfSXrd)"><path class="z-9i_8bfl"/></g><g filter="url(#iC0sy0d)"><path class="hjqblrkqp"/></g><g filter="url(#i4R02rc)"><path class="j70q-ob_s"/></g><g filter="url(#iE0whpd)"><path class="ippwcttje"/></g><path class="j8ko_gbga"/><path fill="url(#iFgWXhd)" class="ijw_rnn7a"/><path class="z-wayobeo"/><g filter="url(#ipywxUc)"><path class="rsnhbx34n"/><path fill="url(#iGK0t6q)" class="x1mtd7bby"/></g><g filter="url(#ik2wr7d)"><path fill="url(#icYVICe)" class="h66xyjd8c"/></g><path class="kjs7dva7o"/><path fill="url(#ikmn3Zd)" class="a_4tfrb5p"/><path class="q7hwrsbld"/><g filter="url(#iLPjrfk)"><path fill="url(#ibo04rw)" class="h9v6ocbal"/></g><g filter="url(#iqOxCub)"><ellipse transform="rotate(-27.914 13.252 9.96)" class="m4sl5db0r"/><ellipse fill="url(#iPKxFCd)" transform="rotate(-27.914 13.252 9.96)" class="qd_4q9b3f"/></g><g filter="url(#i6qxU9d)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#i1ymVDc)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iyrOtsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35936 2.32814 -1.13833 -.66466 10.898 7.792)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="cmxem9b7n"/><stop offset="1" class="akif0u8-c"/></radialGradient><radialGradient id="i7oZiJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.82081 0 0 2.98547 20.212 7.694)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="pauz_6a2q"/><stop offset="1" class="fajdpunlk"/></radialGradient><radialGradient id="igvRrqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41088 5.24241 -6.25056 -1.6822 14.758 12.65)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="r0oy6qbbb"/><stop offset="1" class="fe_2ojbxo"/></radialGradient><radialGradient id="iwtLm3r" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.998 12.054)scale(1.81196 3.24827)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="wnf6rgd_w"/><stop offset="1" class="r3cifybsp"/></radialGradient><radialGradient id="iRlvw5c" cx="0" cy="0" r="1" gradientTransform="rotate(147.269 4.65 10.005)scale(2.65864 2.62008)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="f-d4mvczx"/><stop offset="1" class="bwphqzbzj"/></radialGradient><radialGradient id="i8g26lb" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="cdn41be_i"/><stop offset="1" class="tziry6b6t"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iblgbvb" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.39 19.816)scale(1.95067 1.56677)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="ibrdWNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.245 24.594)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i024Txd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.113 25.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ieWdNxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 22.927 27.297)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iqGuoib" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 22.832 28.564)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iE1PSBb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.323 9.954)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iZ8UhGy" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.684 10.499)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iCKaJkb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.068 9.346)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="ii5z7uc" cx="0" cy="0" r="1" gradientTransform="rotate(155.58 8.627 6.942)scale(8.06812 16.7964)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iyT4fsd" cx="0" cy="0" r="1" gradientTransform="rotate(152.301 7.543 7.523)scale(2.45508 2.07416)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="ix0VL4c" cx="0" cy="0" r="1" gradientTransform="matrix(.8623 -4.13673 5.28493 1.10165 13.514 16.902)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i8ycffu" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.33946 -11.7447 0 15.49 9.471)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="z-4_x36kk"/><stop offset=".881" class="oku_j2z7m"/><stop offset="1" class="ykomykbsb"/></radialGradient><radialGradient id="iMWT1Dc" cx="0" cy="0" r="1" gradientTransform="rotate(164.652 7.418 6.935)scale(5.79367 9.91095)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="isLW6ME" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.131 9.538)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iMniqYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3908 1.60593 0 13.784 9.627)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iVE67xc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38781 0 0 -4.53462 21.01 11.059)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ihRY7vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.75853 -13.8368 0 15.76 6.745)" gradientUnits="userSpaceOnUse"><stop class="p36egv2ks"/><stop offset="1" class="tu2o7vbgm"/></radialGradient><radialGradient id="i5NVrab" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.361 -5.369)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="ibFO5je" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.706 14.396)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iFgWXhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.888 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iGK0t6q" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.313 .745)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikmn3Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.524 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iPKxFCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.238 10.274)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><filter id="iKEe48b" width="16.15" height="13.5" x="7.51" y="4.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.431373 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1945" result="effect2_innerShadow_4002_1945"/></filter><filter id="ilzofLk" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".5"/></filter><filter id="iPg2QYb" width="2.65" height="3.79" x="25.245" y="22.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iXfr0He" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1945"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1945" result="shape"/></filter><filter id="ieBCGYb" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iDAYawb" width="4.352" height="2.789" x="13.564" y="15.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.647059 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iOPhxBc" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iBdq6Yd" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".325"/></filter><filter id="iDk0IXI" width="4.618" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iBlKgXc" width="2.047" height=".25" x="23.378" y="25.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="i654bKc" width="2.047" height=".25" x="23.3" y="27.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="iX7iUyc" width="2.047" height=".25" x="23.378" y="28.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="iHWLdxc" width="1.329" height="2.379" x="9.673" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".125"/></filter><filter id="iA0FRwc" width="1.447" height="2.403" x="20.418" y="9.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".125"/></filter><filter id="ie6VMXd" width="10.5" height="11.523" x="10.51" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="ikFc29c" width="3.877" height="4.9" x="13.56" y="9.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".5"/></filter><filter id="iULXJYb" width="2.077" height="3.1" x="14.667" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="i0M7Wyx" width="3.618" height="1.473" x="13.897" y="13.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="iEfSXrd" width="2.339" height="1.176" x="12.039" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.203922 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iC0sy0d" width="2.339" height="1.176" x="17.162" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.203922 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="i4R02rc" width="2.611" height="1.227" x="16.996" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="iE0whpd" width="2.611" height="1.227" x="11.807" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="ipywxUc" width=".787" height=".696" x="17.154" y="9.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="ik2wr7d" width=".891" height=".913" x="17.994" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".1"/></filter><filter id="iLPjrfk" width=".986" height="1.04" x="13.551" y="9.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".1"/></filter><filter id="iqOxCub" width=".913" height=".705" x="12.796" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1945" stdDeviation=".05"/></filter><filter id="i6qxU9d" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><filter id="i1ymVDc" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1945"/></filter><linearGradient id="iZ2w8Cc" x1="22.414" x2="18.799" y1="6.466" y2="18.596" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset=".864" class="yvo95wbjf"/></linearGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="iCoINWb" x1="14.633" x2="13.72" y1="19.957" y2="18.965" gradientUnits="userSpaceOnUse"><stop class="aq4-jj3gx"/><stop offset="1" class="f5q4vk1vk"/></linearGradient><linearGradient id="i6jO4ud" x1="11.535" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="ovaf-b7lk"/></linearGradient><linearGradient id="iw5yIye" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="k3d1ulbgd"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iQbAUIc" x1="17.352" x2="15.29" y1="17.75" y2="15.906" gradientUnits="userSpaceOnUse"><stop class="wef4_oh4f"/><stop offset="1" class="r7u5ujbtr"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iEYHwqd" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iYEUgQc" x1="25.184" x2="23.348" y1="25.992" y2="25.992" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i5g22Rd" x1="25.105" x2="23.27" y1="27.297" y2="27.297" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iYxUmRb" x1="25.184" x2="23.348" y1="28.602" y2="28.602" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i51UrPe" x1="22.142" x2="20.935" y1="10.021" y2="12.197" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="i6Qchqd" x1="9.856" x2="11.314" y1="10.725" y2="10.598" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iZn0Whb" x1="15.706" x2="16.561" y1="11.685" y2="11.685" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iVedWob" x1="14.633" x2="15.707" y1="11.53" y2="11.589" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ibACQQb" x1="15.706" x2="15.706" y1="12.084" y2="12.936" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ioyX2Cb" x1="15.706" x2="15.706" y1="9.836" y2="10.853" gradientUnits="userSpaceOnUse"><stop class="m7nbcacrv"/><stop offset="1" class="l5m23db_l"/><stop offset="1" class="rnayv3xgs"/></linearGradient><linearGradient id="icYVICe" x1="18.666" x2="18.352" y1="10.11" y2="10.303" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibo04rw" x1="14.268" x2="13.954" y1="10.11" y2="10.303" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mechanic" /></template>
<style>
.a_4tfrb5p {
  d: path("M13.522 9.579a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.akif0u8-c {
  stop-color: var(--svg-color--d66913, #D66913);
  stop-opacity: 0;
}

.aq4-jj3gx {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
}

.b73qugbel {
  d: path("M20.628 12.197q.1-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bscxqsbmf {
  d: path("M23.51 10.724c0-1.722-2.299-2.453-2.299-3.474l-.14-.68c0-.92.252-1.39-.103-2.011H10.65c-.306.62-.394 1.784-.394 2.704v.01c0 1.048-2.247 1.352-2.247 3.45c0 .541.118 1.041.335 1.502c.069.15.069.33 0 .48a3.4 3.4 0 0 0-.335 1.481c0 1.862 1.488 3.373 3.32 3.373h8.86c1.832 0 3.32-1.511 3.32-3.373c0-.53-.118-1.03-.335-1.48a.58.58 0 0 1 0-.481c.217-.46.335-.971.335-1.501");
}

.builfkb8w {
  d: path("m15.324 10.142l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.bwphqzbzj {
  stop-color: var(--svg-color--e298b3, #E298B3);
  stop-opacity: 0;
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cdn41be_i {
  stop-color: var(--svg-color--e49da8, #E49DA8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmxem9b7n {
  stop-color: var(--svg-color--d66913, #D66913);
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cuk6lqbzk {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.669 9.659a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.duc38e2qw {
  fill: var(--svg-color--ffe9ff, #FFE9FF);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.f-d4mvczx {
  stop-color: var(--svg-color--e298b3, #E298B3);
}

.f3w949b_d {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.344 13.38c.393.205.862.323 1.362.323c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04c.058.06.079.155.02.241m-2.986-.28l2.945.252m-2.945-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.253m3.208.028l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869c-.682 0-1.28-.348-1.625-.868m3.208-.029a1.9 1.9 0 0 1-1.583.847a1.9 1.9 0 0 1-1.583-.847m-.042.029l.042-.029m-.042.029v-.001l.042-.027");
}

.f5q4vk1vk {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
  stop-opacity: 0;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fajdpunlk {
  stop-color: var(--svg-color--f89c1a, #F89C1A);
  stop-opacity: 0;
}

.fe_2ojbxo {
  stop-color: var(--svg-color--ed5f25, #ED5F25);
  stop-opacity: 0;
}

.fgv70eb9t {
  fill: var(--svg-color--ffe3f6, #FFE3F6);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.fjwq502mo {
  d: path("M10.652 8.998a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h66xyjd8c {
  d: path("M18.685 10.354a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.h9v6ocbal {
  d: path("M14.337 10.366c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hjqblrkqp {
  fill: var(--svg-color--932929, #932929);
  d: path("M19.145 8.047a2.77 2.77 0 0 0-1.739-.36a.277.277 0 1 0 .067.551a2.22 2.22 0 0 1 1.387.285a1 1 0 0 1 .091.06l.003.002a.277.277 0 0 0 .34-.439z");
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hxqcnhbrq {
  d: path("M15.706 13.753c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.208c.335.508.918.847 1.583.847s1.248-.339 1.583-.847c.086-.129-.06-.278-.198-.208a3 3 0 0 1-1.385.328");
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijw_rnn7a {
  d: path("M17.89 9.579a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.ippwcttje {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.2 9.241c.765.04 1.099.422 1.218.614l-2.011.46c-.141.008-.485-.085-.563-.245a.31.31 0 0 1 .05-.364c.177-.203.675-.497 1.306-.465");
}

.j70q-ob_s {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.215 9.241c-.766.04-1.1.422-1.22.614l2.012.46c.141.008.485-.085.563-.245a.31.31 0 0 0-.05-.364c-.177-.203-.675-.497-1.305-.465");
}

.j8ko_gbga {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.097 9.307c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k3d1ulbgd {
  stop-color: var(--svg-color--fee6ff, #FEE6FF);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kjs7dva7o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.315 9.307c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m4sl5db0r {
  cx: 13.252px;
  cy: 9.96px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.m7nbcacrv {
  stop-color: var(--svg-color--e89633, #E89633);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.oku_j2z7m {
  stop-color: var(--svg-color--f69456, #F69456);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.ovaf-b7lk {
  stop-color: var(--svg-color--ffeaff, #FFEAFF);
  stop-opacity: 0;
}

.p36egv2ks {
  stop-color: var(--svg-color--e07a2d, #E07A2D);
}

.pauz_6a2q {
  stop-color: var(--svg-color--f89c1a, #F89C1A);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.phyw90buy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.425 27.297h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q7hwrsbld {
  fill: var(--svg-color--000, #000);
  d: path("M14.033 10.471a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qd_4q9b3f {
  cx: 13.252px;
  cy: 9.96px;
  rx: 0.39px;
  ry: 0.197px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0-_ekb3n {
  d: path("M19.796 7.274h-3.314c-1.314 0-2.508-.594-3.245-1.657a.272.272 0 0 0-.478.05l-.08.194a2.34 2.34 0 0 1-1.233 1.238a.4.4 0 0 1-.11.048c-.249.117-.816.488-.826 1.453l.14 3.235c.119 2.865 2.378 4.785 5.115 4.785s4.996-1.92 5.116-4.785l.129-3.08c-.02-1.354-1.025-1.48-1.214-1.48");
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r0oy6qbbb {
  stop-color: var(--svg-color--ed5f25, #ED5F25);
}

.r3cifybsp {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
  stop-opacity: 0;
}

.r7u5ujbtr {
  stop-color: var(--svg-color--faa236, #FAA236);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rg9aui68e {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.22 10.338l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.542-.408-.661 0");
}

.rnayv3xgs {
  stop-color: var(--svg-color--e89633, #E89633);
  stop-opacity: 0;
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.rsnhbx34n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.824 9.767c.064.085-.069.189-.22.302s-.263.192-.327.107s.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tu2o7vbgm {
  stop-color: var(--svg-color--e07a2d, #E07A2D);
  stop-opacity: 0;
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.tziry6b6t {
  stop-color: var(--svg-color--e49da8, #E49DA8);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vz0qjzgsj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 28.602H25.3");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.waqwqw1tk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 25.992H25.3");
}

.wef4_oh4f {
  stop-color: var(--svg-color--ffca3b, #FFCA3B);
}

.wnf6rgd_w {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x1mtd7bby {
  d: path("M17.824 9.767c.064.085-.069.189-.22.302s-.263.192-.327.107s.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ykomykbsb {
  stop-color: var(--svg-color--ff996b, #FF996B);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yvo95wbjf {
  stop-color: var(--svg-color--f47c2d, #F47C2D);
}

.z-4_x36kk {
  stop-color: var(--svg-color--f69456, #F69456);
  stop-opacity: 0;
}

.z-9i_8bfl {
  fill: var(--svg-color--932929, #932929);
  d: path("M12.295 8.047a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-wayobeo {
  fill: var(--svg-color--000, #000);
  d: path("M17.379 10.471c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z84sqrd2n {
  d: path("M15.717 18.667c-1.523-.508-1.95-1.487-2.153-2.589h4.352c-.367 2.016-1.68 2.488-2.199 2.59");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zuj_hmbed {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.668 11.546q.058-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
