<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7WI3ab)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#iHjRGTb)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path class="eflfs0b6d"/><path fill="url(#ixTcHpd)" class="x5s8xacrq"/><path fill="url(#iotA9Kc)" class="x5s8xacrq"/><path fill="url(#iTfaoud)" class="x5s8xacrq"/><g filter="url(#iTLHLye)"><path fill="url(#i9jhx2c)" class="bb2fbgrpu"/></g><g filter="url(#i1Q4xKc)"><path class="fb6lhwb5h"/><path fill="url(#i1uDSQQ)" class="gejm97-ji"/><path fill="url(#ic8hQib)" class="gejm97-ji"/><path fill="url(#ihilr9b)" class="gejm97-ji"/></g><g filter="url(#iJeuOcd)"><path class="vm-1lsb4c"/><path fill="url(#i9Cev1V)" class="yr50mjbls"/><path fill="url(#ivYMupe)" class="yr50mjbls"/></g><g filter="url(#imEN5bd)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#iYoJGbc)"><path class="acqsg9pcz"/><path fill="url(#iqYEFRc)" class="lrtdxszpp"/></g><g filter="url(#iihuKac)"><path stroke="url(#iFIIACe)" class="izop3bc_a"/></g><g filter="url(#iNLhged)"><path stroke="url(#iFh5wUb)" class="aqae8acff"/></g><g filter="url(#iO3gvFt)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><g filter="url(#i9Y4UId)"><path stroke="url(#is2RVse)" class="lk8uk6bqv"/></g><g filter="url(#iTrq1Le)"><path class="birxs8bma"/></g><g filter="url(#iZScIMc)"><path stroke="url(#ihS1G2H)" class="w-3uv5bmy"/></g><g filter="url(#inxyTnd)"><path stroke="url(#iS5mqIb)" class="ry_er4bde"/></g><path fill="url(#iPJ6dNd)" class="cauw2cc8b"/><path fill="url(#iy6IrHe)" class="a8hdpdqmy"/><g filter="url(#iO1F2Pc)"><path fill="url(#irpW1Wc)" class="w7yz-z7ot"/><path fill="url(#ienzh7b)" class="w7yz-z7ot"/></g><path fill="url(#it1OPse)" class="w7yz-z7ot"/><path fill="url(#i0fO6Ed)" class="w7yz-z7ot"/><path fill="url(#i5cwqnd)" class="w7yz-z7ot"/><path fill="url(#i3kYFEb)" class="w7yz-z7ot"/><path fill="url(#ic0G2nc)" class="w7yz-z7ot"/><path fill="url(#iNGqMNd)" class="w7yz-z7ot"/><path fill="url(#id2Zwte)" class="w7yz-z7ot"/><path fill="url(#iyegewd)" class="w7yz-z7ot"/><g filter="url(#iPvspZb)"><path class="nyc30sbjl"/></g><g filter="url(#ixv590d)"><path class="xkav3fbel"/><path fill="url(#i8epw9b)" class="rexswfp7u"/><path fill="url(#i338dzd)" class="rexswfp7u"/><path fill="url(#icf1Epb)" class="rexswfp7u"/><path fill="url(#iqsc7ob)" class="rexswfp7u"/><path fill="url(#irm8Uui)" class="rexswfp7u"/></g><g filter="url(#iggrk7b)"><path stroke="url(#iFwwV4d)" class="j-4ca8b1h"/></g><path fill="url(#iEqcDbd)" class="l9tmrkb9g"/><g filter="url(#iWWESRd)"><path fill="url(#iUasPpb)" class="yeua67bbv"/></g><path fill="url(#iZC1Vle)" class="yeua67bbv"/><path fill="url(#iUAnttb)" class="yeua67bbv"/><path fill="url(#i7pgW2c)" class="yeua67bbv"/><g filter="url(#iHueyHL)"><path class="k0_5jrdam"/></g><g filter="url(#iPGC1eO)"><path class="zmgvejj5n"/></g><g filter="url(#iNN04Jd)"><path class="c1plhpdzv"/><path fill="url(#ir8JMLX)" class="g2ja09knc"/><path fill="url(#iOVZ0mb)" class="g2ja09knc"/></g><g filter="url(#ieWes5d)"><path class="gmxcoyb3w"/><path fill="url(#iSs5O7b)" class="ym9fg6bfq"/><path fill="url(#idlH3be)" class="ym9fg6bfq"/><path fill="url(#izWsjed)" class="ym9fg6bfq"/></g><path class="zn0daq-ec"/><path fill="url(#iK1jikb)" class="tlfg_z2ba"/><path class="skyuexbly"/><g filter="url(#imiW5Bb)"><path class="n9_mfqbiz"/><path fill="url(#iTTIZ9b)" class="kcopl3yfj"/></g><g filter="url(#ie5PEol)"><path fill="url(#ijaSrJd)" class="auvxa4bjy"/></g><path class="bzzm1qsgu"/><path fill="url(#iebeYwb)" class="q0hx2xlra"/><path class="ge_0gybcs"/><g filter="url(#i4jkD2b)"><path fill="url(#iy7bv0b)" class="dvccaha7q"/></g><g filter="url(#izlk1Mc)"><ellipse transform="rotate(-27.914 16.107 6.566)" class="bfmahjb2k"/><ellipse fill="url(#i4TWNTb)" transform="rotate(-27.914 16.107 6.566)" class="cx0l5g7xw"/></g><path fill="url(#iLRFLdo)" class="onsnjwb6t"/><path fill="url(#iGJYrbe)" class="onsnjwb6t"/><path fill="url(#iVJ3ivc)" class="onsnjwb6t"/><path fill="url(#i3TsyFd)" class="onsnjwb6t"/><path fill="url(#iKic4Xd)" class="t3e-4m9eh"/><path fill="url(#imIp5Jc)" class="t3e-4m9eh"/><g filter="url(#ijhOLvb)"><path fill="url(#iv95Czb)" class="w432wxblv"/></g><g filter="url(#i6oJutc)"><path fill="url(#iK13lfc)" class="vlmsfkb7s"/></g><g filter="url(#iYQbuQd)"><path class="glr2hkbig"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iotA9Kc" cx="0" cy="0" r="1" gradientTransform="rotate(-49.88 21.65 1.225)scale(1.27707 1.06889)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="pth5aoq3a"/><stop offset="1" class="mx89l3bal"/></radialGradient><radialGradient id="iTfaoud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8737 -1.06183 0 7.249 16.475)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="j9wxqsgli"/><stop offset="1" class="nfq1ehtek"/></radialGradient><radialGradient id="ic8hQib" cx="0" cy="0" r="1" gradientTransform="matrix(.88953 2.91279 -1.06086 .32398 23.622 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="mf78xacle"/><stop offset="1" class="ejzj97bwu"/></radialGradient><radialGradient id="ihilr9b" cx="0" cy="0" r="1" gradientTransform="matrix(.53214 0 0 2.90625 23.327 8.716)" gradientUnits="userSpaceOnUse"><stop class="coovcopqe"/><stop offset="1" class="lowqmmb4q"/></radialGradient><radialGradient id="i9Cev1V" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 .46875 -.2011 -.24468 25.71 7.406)" gradientUnits="userSpaceOnUse"><stop class="fkmin4duu"/><stop offset="1" class="b1mtrsw-m"/></radialGradient><radialGradient id="ivYMupe" cx="0" cy="0" r="1" gradientTransform="rotate(-140.258 14.327 -.219)scale(.90426 .73334)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="hkvecca0z"/><stop offset="1" class="ctfh7bufq"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><radialGradient id="iqYEFRc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47103 2.30187 -1.86833 -2.81728 17.116 9.537)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="s9ssdrbqj"/><stop offset="1" class="y_nfvya9e"/></radialGradient><radialGradient id="iPJ6dNd" cx="0" cy="0" r="1" gradientTransform="matrix(.42967 1.15888 -1.37666 .51042 20.242 7.687)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iy6IrHe" cx="0" cy="0" r="1" gradientTransform="matrix(.84724 .26628 -.82148 2.6138 14.04 7.968)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="irpW1Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.69991 0 0 -4.77611 19.126 7.147)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ienzh7b" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.244 7.476)scale(1.93324 1.59604)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="i0fO6Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.64304 -8.71927 0 17.542 4.045)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="l8ndgrbku"/><stop offset="1" class="i4_pmwbhy"/></radialGradient><radialGradient id="i5cwqnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65896 .81547 0 18.92 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="i3kYFEb" cx="0" cy="0" r="1" gradientTransform="matrix(.00226 -.62793 .68334 .00245 16.195 6.42)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ic0G2nc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.62 4.164)scale(4.88499 12.4787)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iNGqMNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.94288 -1.67357 .49434 .5739 13.617 5.578)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="id2Zwte" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.857 12.158)scale(1.43943 .5754)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iyegewd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50015 -.96014 0 16.243 6.862)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i338dzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .14008 -.44023 0 17.782 7.927)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iqsc7ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.97096 .43043 -.69174 -1.56042 17.849 7.6)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iEqcDbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2521 -.61557 2.47658 5.0375 17.233 9.226)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iZC1Vle" cx="0" cy="0" r="1" gradientTransform="matrix(1.57269 -4.10267 5.82164 2.23163 14.24 6.042)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iUAnttb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 12.8 -5.215)scale(3.8605 5.47802)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="i7pgW2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.6496 -1.36755 1.61442 -.76686 19.368 3.615)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="ir8JMLX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26308 0 0 -.46878 17.66 3.02)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iOVZ0mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8467 -2.92394 3.23942 2.04595 14.398 5.282)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iSs5O7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.01714 -1.62397 2.5168 3.12614 18.616 4.487)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="idlH3be" cx="0" cy="0" r="1" gradientTransform="matrix(1.6979 -1.51964 2.78207 3.1084 19.026 5.208)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="izWsjed" cx="0" cy="0" r="1" gradientTransform="rotate(12.654 -9.509 85.643)scale(1.89685 .79417)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iK1jikb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46556 -.74053 0 18.767 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iTTIZ9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1329 -.17127 .2358 -.18298 18.636 6.669)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iebeYwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46559 -.74057 0 16.263 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4TWNTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00443 -.28315 .34036 -.00533 16.098 6.746)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGJYrbe" cx="0" cy="0" r="1" gradientTransform="matrix(.36068 1.28726 -1.22815 .34412 20.165 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iVJ3ivc" cx="0" cy="0" r="1" gradientTransform="matrix(.45206 -.62037 .52 .37891 20.371 6.941)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i3TsyFd" cx="0" cy="0" r="1" gradientTransform="matrix(.33684 -.88969 1.18874 .45006 20.437 7.04)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="imIp5Jc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95156 0 0 -1.06256 14.694 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iv95Czb" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 7.05 4.125)scale(.5336 .5471)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="i7WI3ab" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1296" result="effect2_innerShadow_4002_1296"/></filter><filter id="iHjRGTb" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".5"/></filter><filter id="iTLHLye" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.415686 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.364706 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1296" result="effect2_innerShadow_4002_1296"/></filter><filter id="i1Q4xKc" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.372549 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="iJeuOcd" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="imEN5bd" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="iYoJGbc" width="4.212" height="3.197" x="15.358" y="10.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.333333 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="iihuKac" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".2"/></filter><filter id="iNLhged" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".2"/></filter><filter id="iO3gvFt" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".2"/></filter><filter id="i9Y4UId" width="4.07" height="2.867" x="20.64" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".25"/></filter><filter id="iTrq1Le" width="2.394" height="7.066" x="24.256" y="7.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".3"/></filter><filter id="iZScIMc" width="2.251" height="3.579" x="23.392" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".2"/></filter><filter id="inxyTnd" width="6.781" height="4.219" x="7.807" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".25"/></filter><filter id="iO1F2Pc" width="6.865" height="7.182" x="14.609" y="3.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1296" result="effect2_innerShadow_4002_1296"/></filter><filter id="iPvspZb" width="3.002" height="3.664" x="15.932" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".5"/></filter><filter id="ixv590d" width="1.177" height="1.764" x="16.926" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".025"/></filter><filter id="iggrk7b" width="2.047" height=".816" x="16.491" y="8.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".025"/></filter><filter id="iWWESRd" width="7.387" height="5.008" x="13.821" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1296" result="effect2_innerShadow_4002_1296"/></filter><filter id="iHueyHL" width="1.385" height=".768" x="18.427" y="4.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="iPGC1eO" width="1.385" height=".76" x="15.41" y="4.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/></filter><filter id="iNN04Jd" width="3.791" height="3.444" x="14.018" y="2.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feGaussianBlur result="effect2_foregroundBlur_4002_1296" stdDeviation=".075"/></filter><filter id="ieWes5d" width="4.42" height="3.605" x="17.511" y="2.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1296"/><feGaussianBlur result="effect2_foregroundBlur_4002_1296" stdDeviation=".075"/></filter><filter id="imiW5Bb" width=".536" height=".484" x="18.303" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".05"/></filter><filter id="ie5PEol" width=".682" height=".694" x="18.742" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".1"/></filter><filter id="i4jkD2b" width=".736" height=".767" x="16.193" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".1"/></filter><filter id="izlk1Mc" width=".609" height=".489" x="15.802" y="6.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".05"/></filter><filter id="ijhOLvb" width=".976" height="1.578" x="13.919" y="6.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".125"/></filter><filter id="i6oJutc" width="1.462" height="2.009" x="19.913" y="5.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".25"/></filter><filter id="iYQbuQd" width="3.219" height="1.887" x="18.028" y="2.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1296" stdDeviation=".25"/></filter><linearGradient id="ixTcHpd" x1="6.762" x2="7.023" y1="16.843" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="pmjkxjbis"/><stop offset="1" class="chqodfbvj"/></linearGradient><linearGradient id="i9jhx2c" x1="10.656" x2="11.312" y1="14.335" y2="16.773" gradientUnits="userSpaceOnUse"><stop class="k_twm3bre"/><stop offset="1" class="sz6tlqb9k"/></linearGradient><linearGradient id="i1uDSQQ" x1="22.218" x2="22.984" y1="14.335" y2="12.945" gradientUnits="userSpaceOnUse"><stop class="h5esthbms"/><stop offset="1" class="ygl91-blb"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFh5wUb" x1="10.518" x2="8.203" y1="25.808" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="is2RVse" x1="24.406" x2="22.549" y1="14.21" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".358" class="lmj1w9btz"/><stop offset="1" class="o8is8sb0e"/></linearGradient><linearGradient id="ihS1G2H" x1="24.517" x2="24.517" y1="7.765" y2="10.144" gradientUnits="userSpaceOnUse"><stop offset=".355" class="q657-0bgt"/><stop offset="1" class="riw0hsbxa"/></linearGradient><linearGradient id="iS5mqIb" x1="13.839" x2="13.674" y1="13.023" y2="17.912" gradientUnits="userSpaceOnUse"><stop class="wlyc4ie_v"/><stop offset="1" class="w67edxgfq"/></linearGradient><linearGradient id="it1OPse" x1="20.474" x2="19.023" y1="8.114" y2="8.114" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="i8epw9b" x1="17.996" x2="17.515" y1="7.534" y2="7.554" gradientUnits="userSpaceOnUse"><stop class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="icf1Epb" x1="17.515" x2="17.515" y1="8.187" y2="7.921" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="irm8Uui" x1="17.515" x2="17.515" y1="6.743" y2="7.295" gradientUnits="userSpaceOnUse"><stop class="l69ut4_ru"/><stop offset="1" class="ep7pobc5p"/></linearGradient><linearGradient id="iFwwV4d" x1="16.825" x2="17.008" y1="9.089" y2="8.61" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iUasPpb" x1="21.447" x2="14.783" y1="3.897" y2="3.897" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="ijaSrJd" x1="19.213" x2="19.033" y1="6.652" y2="6.762" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iy7bv0b" x1="16.689" x2="16.509" y1="6.652" y2="6.762" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLRFLdo" x1="21.208" x2="20.516" y1="6.667" y2="7.916" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iKic4Xd" x1="14.158" x2="14.995" y1="7.071" y2="6.998" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iK13lfc" x1="20.644" x2="20.644" y1="6.49" y2="7.499" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople-medium" /></template>
<style>
.a8hdpdqmy {
  d: path("M14.725 7.864a.94.94 0 0 1-.519-.177v.534c0 .512.305.969.77 1.158a2.4 2.4 0 0 1-.199-.677z");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.acqsg9pcz {
  fill: var(--svg-color--b08370, #B08370);
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aqae8acff {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.473c.41.163 1.402.784 2.096 1.97");
}

.auvxa4bjy {
  d: path("M19.224 6.791a.5.5 0 0 0-.133-.265l-.149.164l.068.13z");
}

.b1mtrsw-m {
  stop-color: var(--svg-color--b49381, #B49381);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bb2fbgrpu {
  d: path("m6.569 15.067l-.755.857a.526.526 0 0 0 .776.71l.554-.583a.384.384 0 0 1 .476-.065l.018.01a.1.1 0 0 1 .019.155l-.317.316a.528.528 0 0 0 .716.774l.557-.479a.2.2 0 0 1 .13-.048h1.765a2.5 2.5 0 0 0 1.64-.613l2.365-2.055v-3.25c-.257.025-.59.285-.723.418l-3.247 3.04a.5.5 0 0 1-.284.132l-3.068.355a.98.98 0 0 0-.622.326");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfmahjb2k {
  cx: 16.107px;
  cy: 6.566px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.223px;
  ry: 0.113px;
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.birxs8bma {
  stroke: var(--svg-color--b9937f, #B9937F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.156 14.007v-3.781l.594-.406V8.742");
}

.bzzm1qsgu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.143 6.191a.8.8 0 0 0-.778.608c-.025.1.051.195.154.195h1.28a.132.132 0 0 0 .13-.156a.804.804 0 0 0-.786-.647");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c1plhpdzv {
  fill: var(--svg-color--533634, #533634);
  d: path("m17.648 3.923l-.038-.078a.38.38 0 0 0-.354-.24h-.73a1.93 1.93 0 0 0-1.917 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.448-.926.734-1.124c.08-.056.149-.103.19-.145l.057-.06c.2-.213.558-.592 1.182-.758a3 3 0 0 1 .52-.086c.471-.036.808.377.808.85v.506z");
}

.cauw2cc8b {
  d: path("M20.304 7.864a.94.94 0 0 0 .52-.177v.534c0 .512-.306.969-.77 1.158q.147-.312.199-.677z");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.chqodfbvj {
  stop-color: var(--svg-color--a27c6e, #A27C6E);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.coovcopqe {
  stop-color: var(--svg-color--916958, #916958);
}

.ctfh7bufq {
  stop-color: var(--svg-color--895b49, #895B49);
  stop-opacity: 0;
}

.cx0l5g7xw {
  cx: 16.107px;
  cy: 6.566px;
  rx: 0.223px;
  ry: 0.113px;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dqd47gnac {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
  stop-opacity: 0;
}

.dvccaha7q {
  d: path("M16.729 6.799c0-.166-.135-.276-.17-.31l-.166.16l.101.208z");
}

.dw0qvsbps {
  stop-color: var(--svg-color--ff8738, #FF8738);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eflfs0b6d {
  fill: var(--svg-color--805755, #805755);
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.ejzj97bwu {
  stop-color: var(--svg-color--925e5d, #925E5D);
  stop-opacity: 0;
}

.ep7pobc5p {
  stop-color: var(--svg-color--a2756b, #A2756B);
  stop-opacity: 0;
}

.fb6lhwb5h {
  fill: var(--svg-color--ac866c, #AC866C);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fkmin4duu {
  stop-color: var(--svg-color--b49381, #B49381);
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g2ja09knc {
  d: path("m17.648 3.923l-.038-.078a.38.38 0 0 0-.354-.24h-.73a1.93 1.93 0 0 0-1.917 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.448-.926.734-1.124c.08-.056.149-.103.19-.145l.057-.06c.2-.213.558-.592 1.182-.758a3 3 0 0 1 .52-.086c.471-.036.808.377.808.85v.506z");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ge_0gybcs {
  fill: var(--svg-color--000, #000);
  d: path("M16.554 6.859a.29.29 0 0 0-.293-.293a.292.292 0 0 0-.26.428h.518a.3.3 0 0 0 .035-.135");
}

.gejm97-ji {
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.glr2hkbig {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.039 3.926h-1.226a.284.284 0 1 1 .045-.567c.318.051.74.122 1.024.192c.64.159.816.47.865.692a.9.9 0 0 0-.708-.317");
}

.gmxcoyb3w {
  fill: var(--svg-color--563936, #563936);
  d: path("m20.506 5.799l-.017-.363a.843.843 0 0 0-.806-.818h-.804a1.39 1.39 0 0 1-1.219-.722s.414-1.194 1.1-1.04c.5.114 1.037.291 1.447.559c1.001.653.826 1.83.299 2.384");
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h5esthbms {
  stop-color: var(--svg-color--9f656a, #9F656A);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hkvecca0z {
  stop-color: var(--svg-color--895b49, #895B49);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i4_pmwbhy {
  stop-color: var(--svg-color--925962, #925962);
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.izop3bc_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.516 4.469-2.414");
}

.j-4ca8b1h {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.515 8.809c-.292 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.192.291.527.486.909.486c.381 0 .716-.195.908-.486c.05-.074-.035-.16-.113-.12c-.23.12-.501.189-.795.189Z");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9wxqsgli {
  stop-color: var(--svg-color--91597a, #91597A);
  stop-opacity: 0;
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k_twm3bre {
  stop-color: var(--svg-color--95715f, #95715F);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k0_5jrdam {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.657 5.437a1.1 1.1 0 0 0-.395-.236c-.174-.055-.393-.07-.695-.033a.16.16 0 1 0 .038.316c.276-.034.445-.016.562.02c.114.036.19.094.28.173a.16.16 0 0 0 .21-.24");
}

.kcopl3yfj {
  d: path("M18.73 6.455c.036.05-.04.109-.126.173c-.087.065-.151.11-.188.062c-.036-.049.005-.14.091-.206c.087-.064.186-.077.223-.029");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l69ut4_ru {
  stop-color: var(--svg-color--a2756b, #A2756B);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l8ndgrbku {
  stop-color: var(--svg-color--9f6b75, #9F6B75);
  stop-opacity: 0;
}

.l9tmrkb9g {
  d: path("M17.515 8.809c-.292 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.192.291.527.486.909.486c.381 0 .716-.195.908-.486c.05-.074-.035-.16-.113-.12c-.23.12-.501.189-.795.189");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk8uk6bqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.39 12.46l2.57 1.367");
}

.lmj1w9btz {
  stop-color: var(--svg-color--b38a7a, #B38A7A);
}

.lowqmmb4q {
  stop-color: var(--svg-color--916958, #916958);
  stop-opacity: 0;
}

.lrtdxszpp {
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mf78xacle {
  stop-color: var(--svg-color--925e5d, #925E5D);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mx89l3bal {
  stop-color: var(--svg-color--704138, #704138);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n9_mfqbiz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.73 6.455c.036.05-.04.109-.126.173c-.087.065-.151.11-.188.062c-.036-.049.005-.14.091-.206c.087-.064.186-.077.223-.029");
}

.nfq1ehtek {
  stop-color: var(--svg-color--91597a, #91597A);
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nyc30sbjl {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m17.284 6.849l-.339 1.055c-.058.217.081.434.278.434h.42c.197 0 .336-.22.278-.434l-.284-1.055c-.06-.234-.289-.234-.353 0");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.o8is8sb0e {
  stop-color: var(--svg-color--b38a7a, #B38A7A);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.onsnjwb6t {
  d: path("M20.34 7.916q.056-.915.105-1.831a.924.924 0 0 1-.106 1.83");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmjkxjbis {
  stop-color: var(--svg-color--a27c6e, #A27C6E);
}

.pth5aoq3a {
  stop-color: var(--svg-color--704138, #704138);
  stop-opacity: 0;
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q0hx2xlra {
  d: path("M16.262 6.347a.512.512 0 0 0-.494.647h.99a.516.516 0 0 0-.496-.647");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q657-0bgt {
  stop-color: var(--svg-color--b38d7e, #B38D7E);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rexswfp7u {
  d: path("m17.295 6.736l-.305 1.055c-.062.217.088.434.3.434h.45c.212 0 .361-.22.3-.434l-.306-1.055c-.065-.233-.37-.233-.439 0");
}

.riw0hsbxa {
  stop-color: var(--svg-color--b38d7e, #B38D7E);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.ry_er4bde {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m13.839 13.023l-2.97 2.719H8.558");
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s9ssdrbqj {
  stop-color: var(--svg-color--603a2f, #603A2F);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.skyuexbly {
  fill: var(--svg-color--000, #000);
  d: path("M18.475 6.859c0-.163.13-.293.293-.293a.292.292 0 0 1 .26.428h-.518a.3.3 0 0 1-.035-.135");
}

.sz6tlqb9k {
  stop-color: var(--svg-color--9e6b76, #9E6B76);
}

.t3e-4m9eh {
  d: path("M14.62 6.077a.923.923 0 0 0 .074 1.839a45 45 0 0 1-.074-1.839");
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.tlfg_z2ba {
  d: path("M18.768 6.347a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vlmsfkb7s {
  d: path("m20.413 7.499l.054-1.01c.23.032.408.245.408.503c0 .278-.207.504-.462.507");
}

.vm-1lsb4c {
  fill: var(--svg-color--a5836b, #A5836B);
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w-3uv5bmy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M23.992 7.765v1.121a.5.5 0 0 0 .146.354l.904.904");
}

.w-8ib2bba {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.955c-.307.353-1.133 1.1-1.885 1.832");
}

.w432wxblv {
  d: path("M14.597 6.459a.548.548 0 0 0 .047 1.078q-.03-.539-.047-1.078");
}

.w67edxgfq {
  stop-color: var(--svg-color--a87a74, #A87A74);
  stop-opacity: 0;
}

.w7yz-z7ot {
  d: path("M14.746 8.733a2.25 2.25 0 0 0 2.23 1.955h1.082a2.25 2.25 0 0 0 2.23-1.955c.068-1.08.136-2.157.186-3.238a.83.83 0 0 0-.791-.821h-.804a1.39 1.39 0 0 1-1.269-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939c0 1.067.067 2.118.137 3.188");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wlyc4ie_v {
  stop-color: var(--svg-color--a87a74, #A87A74);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x5s8xacrq {
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.xkav3fbel {
  fill: var(--svg-color--976b67, #976B67);
  d: path("m17.295 6.736l-.305 1.055c-.062.217.088.434.3.434h.45c.212 0 .361-.22.3-.434l-.306-1.055c-.065-.233-.37-.233-.439 0");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y_nfvya9e {
  stop-color: var(--svg-color--70493c, #70493C);
  stop-opacity: 0;
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yeua67bbv {
  d: path("M20.3 3.335c.296.101.56.307.728.603a1.36 1.36 0 0 1-.06 1.45a.9.9 0 0 0-.156.501v.682a1 1 0 0 0-.383-.154l.045-.922a.83.83 0 0 0-.791-.821h-.804a1.39 1.39 0 0 1-1.269-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.867-1.918 1.939l.018.882a1 1 0 0 0-.413.151V5.89a.9.9 0 0 0-.156-.501a1.37 1.37 0 0 1-.082-1.404c.168-.317.438-.539.746-.646c.329-.117.609-.339.794-.637a1.334 1.334 0 0 1 1.659-.524a.85.85 0 0 0 .685 0a1.334 1.334 0 0 1 1.665.542c.176.293.453.505.776.616");
}

.ygl91-blb {
  stop-color: var(--svg-color--a57173, #A57173);
  stop-opacity: 0;
}

.ym9fg6bfq {
  d: path("m20.506 5.799l-.017-.363a.843.843 0 0 0-.806-.818h-.804a1.39 1.39 0 0 1-1.219-.722s.414-1.194 1.1-1.04c.5.114 1.037.291 1.447.559c1.001.653.826 1.83.299 2.384");
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.zmgvejj5n {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M15.558 5.374a1.6 1.6 0 0 1 .998-.206a.159.159 0 1 1-.04.316a1.27 1.27 0 0 0-.838.19l-.01.007l-.001.002a.16.16 0 0 1-.195-.252z");
}

.zn0daq-ec {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.887 6.191a.8.8 0 0 1 .777.608a.157.157 0 0 1-.153.195h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
