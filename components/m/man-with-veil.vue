<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZlL8kc)"><path fill="url(#i0Fcdcb)" class="o-a76ybrz"/><path fill="url(#iEohn0b)" class="o-a76ybrz"/><path fill="url(#iSPaEJc)" class="o-a76ybrz"/></g><g filter="url(#ifcQNeb)"><path fill="url(#iWA8XjK)" class="vd2eb5byb"/></g><path fill="url(#i78Rj4c)" class="uf2g2bcrf"/><path fill="url(#i637Jve)" class="uf2g2bcrf"/><path fill="url(#iwVE1nb)" class="uf2g2bcrf"/><path fill="url(#iogN4me)" class="uf2g2bcrf"/><g filter="url(#iaxS8er)"><path class="sy7ypcb0s"/></g><g filter="url(#iFbJlHc)"><path class="k2ilbsbtx"/></g><g filter="url(#i0VIBse)"><path fill="url(#i0hT14d)" class="a63sghbgq"/><path fill="url(#iWdoslm)" class="a63sghbgq"/><path fill="url(#iZIdIQc)" class="a63sghbgq"/></g><g filter="url(#iAZrD0f)"><path fill="url(#i1Edxlb)" class="jaco0bb7o"/><path fill="url(#i27dMEd)" class="jaco0bb7o"/><path fill="url(#ivo5cEb)" class="jaco0bb7o"/></g><g filter="url(#iI0hzLe)"><path fill="url(#ioiTVHk)" class="t_2t8cb1m"/><path fill="url(#iqu5QTl)" class="t_2t8cb1m"/><path fill="url(#iYQefse)" class="t_2t8cb1m"/><path fill="url(#iVN90xb)" class="t_2t8cb1m"/><path fill="url(#i4juuFb)" class="t_2t8cb1m"/></g><path fill="url(#ioNeTpc)" class="k6x5-ydec"/><path fill="url(#iw3Px2b)" class="k6x5-ydec"/><g filter="url(#iaEEAgc)"><path class="rc6ooub7j"/></g><g filter="url(#iRtMi7m)"><path fill="url(#iNQWHwe)" class="ixyagfboh"/><path fill="url(#ieOREPc)" class="ixyagfboh"/></g><g filter="url(#iHKmf4c)"><path fill="url(#i8j7FAb)" class="pc_s27b-e"/><path fill="url(#iTyQtYb)" class="pc_s27b-e"/></g><circle fill="url(#iJ6OMAe)" class="bzoaervec"/><circle fill="url(#iuDRmPc)" class="bzoaervec"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.416)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.416)" class="movji7bnz"/><circle fill="url(#idLa3Sb)" class="tt62jabku"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.475)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.475)" class="movji7bnz"/><path fill="url(#ixIedGe)" class="pqfjdobif"/><g filter="url(#ij8I7QX)"><path class="f4l2iebhw"/><path fill="url(#iC1N7Rd)" class="bhrci5bls"/><path fill="url(#iLtUpkc)" class="bhrci5bls"/><path fill="url(#irDpFOk)" class="bhrci5bls"/><path fill="url(#iET76nb)" class="bhrci5bls"/><path fill="url(#i1enAQd)" class="bhrci5bls"/></g><path fill="url(#irXJDYc)" class="sfui_rbny"/><g filter="url(#i9XObIX)"><path class="ndpan0qxr"/><path fill="url(#i2hOM9y)" class="u40f6gb7w"/><path fill="url(#itiR8Dd)" class="u40f6gb7w"/></g><g filter="url(#ipENBiT)"><path class="pc9o7vfrh"/><path fill="url(#iZAGKdc)" class="fwzxwmbzz"/><path fill="url(#iMIHXgb)" class="fwzxwmbzz"/><path fill="url(#iGhKSod)" class="fwzxwmbzz"/><path fill="url(#iX8UZ0b)" class="fwzxwmbzz"/><path fill="url(#ilHrTHb)" class="fwzxwmbzz"/></g><g filter="url(#ix0vbCb)"><path fill="url(#i7qLttb)" clip-rule="evenodd" class="cv36clbgq"/></g><g filter="url(#i8DMVLc)"><path class="wtq6ffhpb"/></g><g filter="url(#iFtA31c)"><path fill="url(#iUqUnnb)" class="dzj81giuc"/><path fill="url(#irM6hKb)" class="dzj81giuc"/></g><g filter="url(#iAqghxe)"><path stroke="url(#iwdkXve)" class="tx9m-rb0s"/></g><g filter="url(#i8Et3Gc)"><path stroke="url(#iS364Od)" class="qc2tvcsqv"/></g><g filter="url(#iCfSwJc)"><path stroke="url(#iL9dyxc)" class="p30o9xbar"/></g><circle fill="url(#i8pUyfd)" class="e11vewb4m"/><g filter="url(#iDcDaDJ)"><circle fill="url(#ixruFob)" class="g0m9vo59z"/></g><g filter="url(#i206eFc)"><circle fill="url(#iTKNPfb)" class="bzbvn17cg"/><circle fill="url(#ieZy2Hc)" class="bzbvn17cg"/></g><g filter="url(#ifMLfkc)"><circle class="bdgrhk9vc"/><circle fill="url(#i0CyFOd)" class="j_o9-7bds"/><circle fill="url(#iv9sQac)" class="j_o9-7bds"/></g><path fill="url(#iGb44Rb)" class="n15fi_j_b"/><path fill="url(#iTmKlfb)" class="n15fi_j_b"/><path fill="url(#i3DcFKA)" class="n15fi_j_b"/><path fill="url(#iVoWElc)" class="n15fi_j_b"/><path fill="url(#isaFDUc)" class="n15fi_j_b"/><g filter="url(#iNgBy3d)"><path class="g36v-590q"/><path fill="url(#iaPjsQb)" class="w0tiwkbiy"/><path fill="url(#iVF9CSc)" class="w0tiwkbiy"/><path fill="url(#ih2u5Ic)" class="w0tiwkbiy"/><path fill="url(#iK1mUrc)" class="w0tiwkbiy"/><path fill="url(#ia0e82c)" class="w0tiwkbiy"/><path fill="url(#itKZoYd)" class="w0tiwkbiy"/></g><path fill="url(#ih3ZrLc)" class="w0tiwkbiy"/><path fill="url(#ivHjDbc)" class="w0tiwkbiy"/><path fill="url(#iGHsEEl)" class="w0tiwkbiy"/><g filter="url(#igSmObc)"><path class="xom6owbud"/></g><g filter="url(#iyjJkme)"><path class="zu1phkl5f"/><path fill="url(#ib7y9Ud)" class="bjoq3zbde"/><path fill="url(#iMPNpCe)" class="bjoq3zbde"/><path fill="url(#iNy7Hme)" class="bjoq3zbde"/></g><g filter="url(#i35nnJc)"><path stroke="url(#i9CxTPV)" class="gheu10dvq"/></g><path class="g7-dulbej"/><path class="yplexji2m"/><path fill="url(#iSMU9me)" class="kbh1z4ejc"/><path class="ix9888zzn"/><g filter="url(#iWBcOZz)"><path class="qeam9vbuh"/><path fill="url(#ia22nEb)" class="bjb91oqpb"/></g><g filter="url(#iGaNw0b)"><path fill="url(#iB3Nowd)" class="jbwzbzbjz"/></g><path class="itdpb1bak"/><path fill="url(#iKi0ueb)" class="s6x_7igsk"/><path class="t0hxrk0wd"/><g filter="url(#ioBGJ3b)"><path fill="url(#iYzlLzb)" class="svrhtgblk"/></g><g filter="url(#ifFrZIc)"><ellipse transform="rotate(-27.914 13.513 9.88)" class="spm-60b8m"/><ellipse fill="url(#iS92FYb)" transform="rotate(-27.914 13.513 9.88)" class="oteajy_lu"/></g><g filter="url(#i2qbruc)"><path fill="url(#iKBvSsc)" clip-rule="evenodd" class="p_-hfd2qm"/></g><g filter="url(#iTYVuDb)"><path class="bv9rw5b1d"/></g><g filter="url(#irBRE3d)"><path fill="url(#izoegMc)" clip-rule="evenodd" class="je3trsb-h"/></g><g filter="url(#ivlEFmb)"><path class="pi0l4_iea"/></g><g filter="url(#ikFuVjb)"><path fill="url(#i5LeVEc)" clip-rule="evenodd" class="j9gcfbbmq"/><path fill="url(#incKDNe)" clip-rule="evenodd" class="j9gcfbbmq"/></g><defs><radialGradient id="iEohn0b" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.835 7.024)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iSPaEJc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.639)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="i78Rj4c" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.151 15.737)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iwVE1nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.014)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="iogN4me" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.17)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iWdoslm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.809)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iZIdIQc" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.637 14.633)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i27dMEd" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.31)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="ivo5cEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.873)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ioiTVHk" cx="0" cy="0" r="1" gradientTransform="matrix(-7.18754 -5.18744 7.28549 -10.09452 19.012 22.139)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="vj4m2tb3q"/><stop offset="1" class="pcshyrb4c"/></radialGradient><radialGradient id="iqu5QTl" cx="0" cy="0" r="1" gradientTransform="rotate(144.144 6.553 11.724)scale(3.36107 1.16956)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="ospx9ybif"/><stop offset="1" class="ruijhiham"/></radialGradient><radialGradient id="iYQefse" cx="0" cy="0" r="1" gradientTransform="rotate(-136.548 13.545 7.484)scale(8.17891 17.4863)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="huxowdbbh"/><stop offset="1" class="ugfb6lv5r"/></radialGradient><radialGradient id="iVN90xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91406 -.74218 .35164 -.43308 22.45 20.725)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="a0lve6l9d"/><stop offset="1" class="g6l_i_bhw"/></radialGradient><radialGradient id="i4juuFb" cx="0" cy="0" r="1" gradientTransform="rotate(155.313 6.31 9.951)scale(4.26479 1.99112)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g5gls_bky"/><stop offset="1" class="lc_l11bld"/></radialGradient><radialGradient id="ioNeTpc" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.748 35.888)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="ieOREPc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.178 4.914)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iTyQtYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.31)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iJ6OMAe" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.314 11.803)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iuDRmPc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.43 14.599)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="idLa3Sb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.35 12.659)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="ixIedGe" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.37 19.37)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="iC1N7Rd" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.293 20.224)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iLtUpkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.48 23.013)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="irDpFOk" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.176 9.225)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iET76nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.811)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="i1enAQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.308 24.593)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="irXJDYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.81)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="i2hOM9y" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.717)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="itiR8Dd" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.73)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iZAGKdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.295)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iMIHXgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.983)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="i7qLttb" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.305 16.637)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iUqUnnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.857)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="irM6hKb" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.244)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="i8pUyfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.547 10.658)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ieZy2Hc" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.113 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="i0CyFOd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.699 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iv9sQac" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.74 10.659)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i3DcFKA" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.50813 -9.71474 0 16.462 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset=".96" class="mq2hl_bez"/></radialGradient><radialGradient id="iVoWElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.319 9.385)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="isaFDUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.756 9.352)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iaPjsQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.666 2.938)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="ih2u5Ic" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.114 -1.885)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iK1mUrc" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 20.201 8.92)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ia0e82c" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 15.194 2.049)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="itKZoYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 20.163 6.435)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ih3ZrLc" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.666 2.049)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="ivHjDbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 11.584 3.31)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iGHsEEl" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 17.124 6.29)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="i9CxTPV" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.886 14.674)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iSMU9me" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 18.151 10.31)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ia22nEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.924 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKi0ueb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.784 10.31)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iS92FYb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.767 -1.546)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKBvSsc" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 18.423 8.457)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="izoegMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 13.516 8.457)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="incKDNe" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.665 8.592)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iZlL8kc" width="21.944" height="26.818" x="4.962" y="3.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="ifcQNeb" width="12.631" height="14.916" x="9.484" y="8.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/><feGaussianBlur result="effect2_foregroundBlur_4002_3408" stdDeviation=".05"/></filter><filter id="iaxS8er" width="5.874" height="5.537" x="6.993" y="23.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".5"/></filter><filter id="iFbJlHc" width="4.98" height="4.054" x="18.51" y="24.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".5"/></filter><filter id="i0VIBse" width="2.973" height="2.006" x="21.47" y="23.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iAZrD0f" width="3.281" height="2" x="20.468" y="25.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iI0hzLe" width="13.965" height="11.381" x="9.149" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.596078 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iaEEAgc" width="10.996" height="6.432" x="11.932" y="21.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".5"/></filter><filter id="iRtMi7m" width="2.973" height="2.006" x="7.658" y="23.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iHKmf4c" width="3.266" height="2" x="8.366" y="25.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="ij8I7QX" width="6.218" height="6.789" x="8.343" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3408" result="effect2_innerShadow_4002_3408"/></filter><filter id="i9XObIX" width="6.218" height="6.639" x="17.574" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3408" result="effect2_innerShadow_4002_3408"/></filter><filter id="ipENBiT" width="6.702" height="6.417" x="12.683" y="20.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="ix0vbCb" width="6.703" height="6.517" x="12.633" y="20.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".15"/></filter><filter id="i8DMVLc" width="3.2" height="3.2" x="14.271" y="22.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".25"/></filter><filter id="iFtA31c" width="2.35" height="2.35" x="14.893" y="23.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iAqghxe" width="1.458" height="2.505" x="15.848" y="20.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".125"/></filter><filter id="i8Et3Gc" width="1.724" height="1.924" x="16.94" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".125"/></filter><filter id="iCfSwJc" width="1.368" height="2.217" x="18.104" y="22.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".125"/></filter><filter id="iDcDaDJ" width="2.992" height="2.992" x="9.722" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".25"/></filter><filter id="i206eFc" width="3.592" height="3.592" x="19.069" y="8.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="ifMLfkc" width="2.992" height="2.992" x="19.244" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".25"/></filter><filter id="iNgBy3d" width="12.614" height="8.301" x="9.664" y="1.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3408" result="effect2_innerShadow_4002_3408"/></filter><filter id="igSmObc" width="3.262" height="4.184" x="14.101" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".375"/></filter><filter id="iyjJkme" width="2.379" height="3.184" x="14.781" y="9.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".125"/></filter><filter id="i35nnJc" width="3.621" height="1.473" x="14.16" y="13.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".05"/></filter><filter id="iWBcOZz" width=".787" height=".697" x="17.417" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".05"/></filter><filter id="iGaNw0b" width=".892" height=".914" x="18.257" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".1"/></filter><filter id="ioBGJ3b" width=".987" height="1.041" x="13.811" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".1"/></filter><filter id="ifFrZIc" width=".914" height=".705" x="13.056" y="9.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".05"/></filter><filter id="i2qbruc" width="2.604" height="1.648" x="17.235" y="7.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="iTYVuDb" width="2.709" height="1.503" x="17.183" y="7.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".2"/></filter><filter id="irBRE3d" width="2.604" height="1.648" x="12.101" y="7.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><filter id="ivlEFmb" width="2.709" height="1.503" x="12.049" y="7.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3408" stdDeviation=".2"/></filter><filter id="ikFuVjb" width="15.448" height="4.54" x="8.283" y="2.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3408"/></filter><linearGradient id="i0Fcdcb" x1="26.906" x2="11.7" y1="11.514" y2="21.514" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iWA8XjK" x1="20.7" x2="10.387" y1="17.42" y2="17.42" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="i637Jve" x1="14.887" x2="14.887" y1="30.889" y2="29.608" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="i0hT14d" x1="23.649" x2="21.867" y1="25.811" y2="24.401" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="i1Edxlb" x1="22.95" x2="21.169" y1="27.395" y2="25.701" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iw3Px2b" x1="12.653" x2="13.255" y1="29.279" y2="28.936" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iNQWHwe" x1="7.856" x2="9.361" y1="24.295" y2="26.115" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="i8j7FAb" x1="9.062" x2="10.843" y1="27.394" y2="25.709" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iGhKSod" x1="14.919" x2="16.7" y1="27.158" y2="22.889" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iX8UZ0b" x1="13.356" x2="16.981" y1="22.92" y2="23.608" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="ilHrTHb" x1="17.231" x2="16.325" y1="26.92" y2="25.17" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iwdkXve" x1="16.477" x2="16.477" y1="20.842" y2="22.85" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iS364Od" x1="17.286" x2="18.153" y1="24.896" y2="26.1" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iL9dyxc" x1="18.728" x2="18.728" y1="22.428" y2="24.045" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="ixruFob" x1="11.218" x2="10.577" y1="10.937" y2="10.937" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iTKNPfb" x1="21.828" x2="21.008" y1="9.566" y2="12.104" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iGb44Rb" x1="20.01" x2="12.366" y1="11.048" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iTmKlfb" x1="10.569" x2="12.884" y1="13.746" y2="13.445" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iVF9CSc" x1="11.105" x2="14.01" y1="10.391" y2="5.231" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="ib7y9Ud" x1="15.105" x2="16.044" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iMPNpCe" x1="16.91" x2="15.883" y1="12.031" y2="12.016" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iNy7Hme" x1="16.165" x2="16.165" y1="12.774" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iB3Nowd" x1="18.93" x2="18.616" y1="10.029" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYzlLzb" x1="14.529" x2="14.215" y1="10.029" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5LeVEc" x1="20.481" x2="8.544" y1="3.67" y2="7.358" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil" /></template>
<style>
.a0lve6l9d {
  stop-color: var(--svg-color--efab25, #EFAB25);
}

.a63sghbgq {
  d: path("M21.48 25.313c.063-.897.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.bdgrhk9vc {
  cx: 20.74px;
  cy: 10.659px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.bhrci5bls {
  d: path("M8.528 22.78c-.076-.156-.018-.355.098-.42c.854-.402 2.333.553 3.222 1.634c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.631l.133.311c.111.293.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.416-1.83.407-2.656-.36c-.34-.302-.754-.948-.972-1.414z");
}

.bjb91oqpb {
  d: path("M18.088 9.687c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.bjoq3zbde {
  d: path("m15.588 10.373l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.bv9rw5b1d {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.367 8.31c-.21-.193-.804-.52-1.66-.44");
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bzbvn17cg {
  cx: 20.74px;
  cy: 10.658px;
  r: 1.671px;
}

.bzoaervec {
  cx: 9.168px;
  cy: 20.518px;
  r: 0.762px;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cv36clbgq {
  fill-rule: evenodd;
  d: path("M13.709 24.354a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.006q-.019-.217.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.395.927 1v.56a.3.3 0 0 0 .396.285l.551-.188l.007-.003c.516-.193 1.023.047 1.16.56c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.469l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.001a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.067z");
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.dzj81giuc {
  d: path("M15.993 25.244a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e11vewb4m {
  cx: 11.218px;
  cy: 10.658px;
  r: 1.671px;
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f4l2iebhw {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.78c-.076-.156-.018-.355.098-.42c.854-.402 2.333.553 3.222 1.634c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.631l.133.311c.111.293.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.416-1.83.407-2.656-.36c-.34-.302-.754-.948-.972-1.414z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwzxwmbzz {
  d: path("M12.712 23.191c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g0m9vo59z {
  cx: 11.218px;
  cy: 10.659px;
  r: 0.996px;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g36v-590q {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.794 4.174l.43.214c.751.374 1.18 1.228 1.02 2.135l-.591 3.043c-.053.314-.26.526-.572.534c.035-.504.068-1.318.081-1.446c.044-.434-.024-.561-.422-.956c-.214-.214-.376-.534-.376-.854v-.855c0-.267-.214-.48-.43-.533c-.643-.16-1.986-.428-3.919-.428c-1.932 0-3.275.267-3.919.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.375.854l-.161.16c-.215.16-.324.495-.324.761c.015.156.036 1.053.06 1.426a.634.634 0 0 1-.595-.532L9.68 6.47c-.107-.854.322-1.708 1.074-2.082c1.015-.445 1.384-1.12 2.201-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.054 2.362.533l.806.801c.214.267.483.427.805.587");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g5gls_bky {
  stop-color: var(--svg-color--ee8a27, #EE8A27);
}

.g6l_i_bhw {
  stop-color: var(--svg-color--efab25, #EFAB25);
  stop-opacity: 0;
}

.g7-dulbej {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.97 13.791c-.507 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.086-.13-.061-.28-.198-.21c-.401.21-.874.33-1.386.33");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gheu10dvq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.97 13.791c-.507 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.086-.13-.061-.28-.198-.21c-.401.21-.874.33-1.386.33Z");
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.huxowdbbh {
  stop-color: var(--svg-color--f8a519, #F8A519);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.itdpb1bak {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.575 9.226c-.653 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.ix9888zzn {
  fill: var(--svg-color--000, #000);
  d: path("M17.642 10.391a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.061-.236");
}

.ixyagfboh {
  d: path("M10.52 25.313c-.063-.897-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.j_o9-7bds {
  cx: 20.74px;
  cy: 10.659px;
  r: 0.996px;
}

.j9gcfbbmq {
  fill-rule: evenodd;
  d: path("M15.972 4.383c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 1 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.914 7.54 2.876A.775.775 0 1 1 22.4 6.788c-.735-.758-2.556-2.405-6.428-2.405");
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jaco0bb7o {
  d: path("M20.61 25.826c.678-.599 1.716-.535 2.297.112l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.jbwzbzbjz {
  d: path("M18.949 10.274a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.je3trsb-h {
  fill-rule: evenodd;
  d: path("M14.19 8.45c-.721-.067-1.183.214-1.295.318a.473.473 0 0 1-.641-.696c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k2ilbsbtx {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.992c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.k6x5-ydec {
  d: path("m13.196 29.95l-2.547-3.836l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kbh1z4ejc {
  d: path("M18.153 9.499a.893.893 0 0 1 .861 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lc_l11bld {
  stop-color: var(--svg-color--ffa821, #FFA821);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mq2hl_bez {
  stop-color: var(--svg-color--ec8c21, #EC8C21);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n15fi_j_b {
  d: path("M10.866 10.045a30 30 0 0 1-.059-1.44c0-.267.108-.587.323-.747l.16-.16c.27-.214.377-.534.377-.855V5.99a.52.52 0 0 1 .43-.534c.643-.16 1.986-.427 3.919-.427c1.932 0 3.275.267 3.919.427c.215.054.43.267.43.534v.854c0 .32.16.641.375.855c.503.352.472.545.43.96c-.013.129-.054 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.ndpan0qxr {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.78c.076-.156.018-.355-.098-.42c-.854-.402-2.334.553-3.222 1.634c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.416 1.83.407 2.656-.36c.34-.302.754-.948.972-1.414z");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.o-a76ybrz {
  d: path("M5.062 16.451c0-8.812 4.89-13.219 10.922-13.219s10.922 4.22 10.922 13.22V29.95H5.062z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ospx9ybif {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
}

.oteajy_lu {
  cx: 13.513px;
  cy: 9.88px;
  rx: 0.39px;
  ry: 0.197px;
}

.p_-hfd2qm {
  fill-rule: evenodd;
  d: path("M17.752 8.45c.72-.067 1.182.214 1.294.318a.473.473 0 1 0 .641-.696c-.306-.282-1.032-.656-2.023-.563a.473.473 0 1 0 .088.941");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p30o9xbar {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.592c.307.135.83.615.461 1.453");
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pc_s27b-e {
  d: path("M11.39 25.826c-.678-.599-1.716-.535-2.298.112l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.pc9o7vfrh {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.191c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.pcshyrb4c {
  stop-color: var(--svg-color--ffbe1d, #FFBE1D);
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pi0l4_iea {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.574 8.31c.21-.193.803-.52 1.659-.44");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqfjdobif {
  d: path("m11.186 26.32l2.71-1.12l-.67-1.62c-.41-1-1.1-1.691-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.137.085 3.001z");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qc2tvcsqv {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.81l.907 1.18");
}

.qeam9vbuh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.088 9.687c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rc6ooub7j {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.427c.096.054.144.22.081.349l-.668 1.39c-.181.388-.526.925-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.665.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.042.223-.058l.036-.084l1.043.853c.063-.129.19-.198.295-.152c.711.328.494-.417.288.729c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruijhiham {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
  stop-opacity: 0;
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s6x_7igsk {
  d: path("M13.782 9.498a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sfui_rbny {
  d: path("m20.799 26.32l-2.71-1.12l.67-1.62c.41-1 1.1-1.691 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.137-.085 3.001z");
}

.spm-60b8m {
  cx: 13.513px;
  cy: 9.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.svrhtgblk {
  d: path("M14.598 10.286c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.sy7ypcb0s {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.163c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.834-2.66.271c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.t_2t8cb1m {
  d: path("M9.15 20.484a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t0hxrk0wd {
  fill: var(--svg-color--000, #000);
  d: path("M14.294 10.391a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.236");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tt62jabku {
  cx: 10.18px;
  cy: 21.596px;
  r: 0.762px;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.tx9m-rb0s {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.045c.324 0 .758.376.758.86v.945");
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u40f6gb7w {
  d: path("M23.457 22.78c.076-.156.018-.355-.098-.42c-.854-.402-2.334.553-3.222 1.634c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.416 1.83.407 2.656-.36c.34-.302.754-.948.972-1.414z");
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uf2g2bcrf {
  d: path("M27 29.951v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.576 5 23.751 5 28.951v1z");
}

.ugfb6lv5r {
  stop-color: var(--svg-color--f8a519, #F8A519);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vd2eb5byb {
  d: path("M9.984 15.874c0-4.854 2.694-7.281 6.016-7.281s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w0tiwkbiy {
  d: path("m20.794 4.174l.43.214c.751.374 1.18 1.228 1.02 2.135l-.591 3.043c-.053.314-.26.526-.572.534c.035-.504.068-1.318.081-1.446c.044-.434-.024-.561-.422-.956c-.214-.214-.376-.534-.376-.854v-.855c0-.267-.214-.48-.43-.533c-.643-.16-1.986-.428-3.919-.428c-1.932 0-3.275.267-3.919.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.375.854l-.161.16c-.215.16-.324.495-.324.761c.015.156.036 1.053.06 1.426a.634.634 0 0 1-.595-.532L9.68 6.47c-.107-.854.322-1.708 1.074-2.082c1.015-.445 1.384-1.12 2.201-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.054 2.362.533l.806.801c.214.267.483.427.805.587");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wtq6ffhpb {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.376a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xom6owbud {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.695 10.536l-.821 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.499-1.7c-.107-.378-.283-.378-.395 0");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yplexji2m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.36 9.227c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zu1phkl5f {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.588 10.373l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
