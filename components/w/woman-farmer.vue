<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijFUiAc)" class="w1rvhsi1q"/><path fill="url(#iq8U6Pc)" class="b1-s7bbow"/><path fill="url(#iuAtIYK)" class="b1-s7bbow"/><g filter="url(#ia8q6hd)"><path fill="url(#innoTqb)" class="cpgq_pqip"/><path fill="url(#iWHqR8d)" class="cpgq_pqip"/></g><g filter="url(#iJUQ5qd)"><path fill="url(#iJOnCsc)" class="arzh1b1yk"/><path fill="url(#ih1ztYb)" class="arzh1b1yk"/><path fill="url(#iLaWwBC)" class="arzh1b1yk"/><path fill="url(#iQvED7c)" class="arzh1b1yk"/><path fill="url(#iStdtke)" class="arzh1b1yk"/><path fill="url(#iApQ8ac)" class="arzh1b1yk"/><path fill="url(#i8NSxev)" class="arzh1b1yk"/></g><g filter="url(#iVGzzzb)"><path fill="url(#iQwF04c)" class="bdkg68dwh"/><path fill="url(#iKdX0Ab)" class="bdkg68dwh"/><path fill="url(#iqYwPrc)" class="bdkg68dwh"/></g><path class="ewu9b2erc"/><path fill="url(#iNIqDne)" class="j6p88_eog"/><path fill="url(#ix0RxQc)" class="y_g2abcid"/><path fill="url(#ivR3Lmv)" class="y_g2abcid"/><path fill="url(#iY8MVRc)" class="bk9jifp6c"/><path fill="url(#ifB5led)" class="bk9jifp6c"/><g filter="url(#iDdpyRd)"><path fill="url(#ikiN20c)" class="q0pd27b8f"/><path fill="url(#iukFimd)" class="q0pd27b8f"/><path fill="url(#ijBBn6d)" class="q0pd27b8f"/></g><path fill="url(#iguY2zp)" class="q0pd27b8f"/><path fill="url(#iyJ8fSc)" class="q0pd27b8f"/><path fill="url(#iQq9Hqd)" class="ato4pubwa"/><path fill="url(#isz5pNe)" class="d81p1wr-c"/><path fill="url(#iybSToK)" class="d81p1wr-c"/><path fill="url(#iy3IF4c)" class="lkb_c2bpv"/><path fill="url(#igXKQBc)" class="lkb_c2bpv"/><path fill="url(#iqkZAkb)" class="lkb_c2bpv"/><path fill="url(#inevGhd)" class="lkb_c2bpv"/><path fill="url(#iclQhPc)" class="lkb_c2bpv"/><g filter="url(#il03aYd)"><path class="py0vwh06s"/></g><g filter="url(#iIuzK7b)"><path fill="url(#iaKCIve)" class="v5c1nslii"/></g><path fill="url(#iTsAmfM)" class="l5iilfaqn"/><path fill="url(#iTgvYde)" class="l5iilfaqn"/><path fill="url(#iIEhdXb)" class="l5iilfaqn"/><path fill="url(#i0gbhpl)" class="gde04ac1w"/><path fill="url(#i061HJN)" class="gde04ac1w"/><path fill="url(#iTjMWab)" class="d9opa32qi"/><path fill="url(#iFOhlhb)" class="d9opa32qi"/><path fill="url(#iuKjv6b)" class="d9opa32qi"/><g filter="url(#i9v2kDe)"><path fill="url(#irbU6sb)" class="a97twobia"/><path fill="url(#iUByWIb)" class="a97twobia"/></g><g filter="url(#iFPv1ee)"><path stroke="url(#iY4kJQe)" class="bewxvkb0d"/></g><g filter="url(#ivmLbUx)"><path stroke="url(#itZIfqb)" class="d6569kbrr"/></g><g filter="url(#iOSLOxc)"><path stroke="url(#iPUO95c)" class="hq-de1bfv"/></g><g filter="url(#iNcQnab)"><path fill="url(#i8ciBVY)" class="h2xkk3unb"/></g><g filter="url(#iNTNF9b)"><path fill="url(#iPe7ltd)" class="e5h9sobbm"/></g><g filter="url(#ia5N2tb)"><path class="n-dwk955l"/><path fill="url(#itBbMvd)" class="j_fcs3b5z"/></g><g filter="url(#iCYpDjd)"><path class="ngmd0gjho"/><path fill="url(#i1zPpnd)" class="z9g4t4ltr"/></g><g filter="url(#i2cCo1b)"><path fill="url(#iybtoVb)" class="nsx0lpbbb"/></g><path fill="url(#i1L6kIR)" class="chk8ftbiu"/><path fill="url(#iL03lyd)" class="chk8ftbiu"/><path fill="url(#i6OETuD)" class="chk8ftbiu"/><g filter="url(#i8byDCe)"><path stroke="url(#izQzJJe)" class="g5fb-ccku"/></g><path fill="url(#ig1fmAe)" class="bauqsdjhx"/><g filter="url(#iLa346G)"><path class="pn0-kabdz"/></g><g filter="url(#ieMajkm)"><path fill="url(#i9DdRyc)" class="c2bt_obzp"/><path fill="url(#iCQg0te)" class="c2bt_obzp"/><path fill="url(#ifawxge)" class="c2bt_obzp"/><path fill="url(#i5Lm3qc)" class="c2bt_obzp"/></g><g filter="url(#iVQJoBc)"><path class="mvc3mwbbx"/></g><g filter="url(#inMrSUb)"><path class="m06r6xc-d"/></g><g filter="url(#iK4YTBb)"><path class="ih9j6q0se"/></g><g filter="url(#igh1ONe)"><path class="sxqibbcpg"/></g><path class="m251pe56x"/><path fill="url(#ihZ1b6c)" class="t5w61l-jh"/><path class="obyiy1bpq"/><g filter="url(#iLFb70N)"><path class="l3_73ztho"/><path fill="url(#ijRE5Kb)" class="jkqn4jkjg"/></g><g filter="url(#iKTw8RE)"><path fill="url(#ioGF3Yv)" class="oaz1a_a-z"/></g><path class="ez9415bai"/><path fill="url(#iNwj34d)" class="sy9dxtbsi"/><path class="a77_r14cc"/><g filter="url(#igb4j6d)"><path fill="url(#iiheKZd)" class="lpz5gxbuh"/></g><g filter="url(#iP0UhLj)"><ellipse transform="rotate(-27.914 13.664 9.95)" class="d8ju_4bds"/><ellipse fill="url(#iYyosWd)" transform="rotate(-27.914 13.664 9.95)" class="it6vkhr5x"/></g><g filter="url(#ikXhIgd)"><path class="t-hnzv4je"/></g><g filter="url(#ijmy1Tb)"><path class="z07lf2bwe"/></g><g filter="url(#iXsO9Nc)"><path class="dhw5gpb4u"/></g><defs><radialGradient id="ijFUiAc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.872 3.9)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iq8U6Pc" cx="0" cy="0" r="1" gradientTransform="scale(8.40625 2.15625)rotate(-90 2.349 0)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iWHqR8d" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.619 3.87)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iJOnCsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.55 16.313)" gradientUnits="userSpaceOnUse"><stop class="fsxgh2bro"/><stop offset=".977" class="w94zsfoim"/></radialGradient><radialGradient id="ih1ztYb" cx="0" cy="0" r="1" gradientTransform="rotate(162.817 11.19 7.444)scale(3.49996 5.18036)" gradientUnits="userSpaceOnUse"><stop class="a39moy9vg"/><stop offset="1" class="kj38e6byz"/></radialGradient><radialGradient id="iLaWwBC" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 1.40625 -3.88891 .17284 18.05 6.5)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="xykughmpx"/><stop offset="1" class="slp9rv7dh"/></radialGradient><radialGradient id="iQvED7c" cx="0" cy="0" r="1" gradientTransform="matrix(4.4973 2.41674 -1.48516 2.76372 20.008 6.856)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="ffx6-fbot"/><stop offset="1" class="vvmps0bsz"/></radialGradient><radialGradient id="iStdtke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32298 -1.3938 1.17894 -1.96489 20.027 9.663)" gradientUnits="userSpaceOnUse"><stop offset=".606" class="k9ocfpb1k"/><stop offset="1" class="kfh4csf0n"/></radialGradient><radialGradient id="iApQ8ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.7283 -1.82122 .56344 .5347 20.677 10.5)" gradientUnits="userSpaceOnUse"><stop class="wjkbrmbdg"/><stop offset="1" class="vpvk9xb4p"/></radialGradient><radialGradient id="i8NSxev" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -1.20313 1.63663 2.69938 18.018 15.828)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="wjcc8nbvz"/><stop offset="1" class="x03fshbgn"/></radialGradient><radialGradient id="iKdX0Ab" cx="0" cy="0" r="1" gradientTransform="rotate(-148.431 6.987 3.163)scale(1.52213 2.93248)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="c14r1779w"/><stop offset="1" class="ox-9gcclq"/></radialGradient><radialGradient id="iqYwPrc" cx="0" cy="0" r="1" gradientTransform="rotate(-134.433 9.888 5.093)scale(4.46383 5.21203)" gradientUnits="userSpaceOnUse"><stop class="la8uztbfo"/><stop offset="1" class="lxps010rs"/></radialGradient><radialGradient id="iNIqDne" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.983 16.225)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="ivR3Lmv" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.84 25.188)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="ifB5led" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 23.014 24.65)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="ikiN20c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16.053 16.094)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="ijBBn6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.199 19.492)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iyJ8fSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.447 15.91)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iQq9Hqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.974 19.592)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="isz5pNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.43272 -4.29817 0 16.662 16.516)" gradientUnits="userSpaceOnUse"><stop class="vooh3tegw"/><stop offset="1" class="xlyybr0fb"/></radialGradient><radialGradient id="iybSToK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.35481 -2.92854 0 15.984 15.27)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="bnge9kbad"/><stop offset="1" class="aum_h2loy"/></radialGradient><radialGradient id="igXKQBc" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.565 11.761)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iclQhPc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.994 18.75)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iTsAmfM" cx="0" cy="0" r="1" gradientTransform="rotate(137.811 9.362 17.164)scale(1.65559 1.3064)" gradientUnits="userSpaceOnUse"><stop class="rht-9g91b"/><stop offset="1" class="fk-65dr-t"/></radialGradient><radialGradient id="iTgvYde" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45313 1.43733 0 26.209 25.094)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="ap8mygb2m"/><stop offset="1" class="qayu9abrk"/></radialGradient><radialGradient id="iIEhdXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 0 0 -3.09375 27.521 24.469)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="nb-_v43xz"/><stop offset=".922" class="ugwoxpb1x"/></radialGradient><radialGradient id="i061HJN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.167 24.71)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iTjMWab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.19 21.531)" gradientUnits="userSpaceOnUse"><stop class="vwnwx2byo"/><stop offset="1" class="vzaknebes"/></radialGradient><radialGradient id="iFOhlhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.692 21.914)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="gr2susb2n"/><stop offset="1" class="vnxqexb9a"/></radialGradient><radialGradient id="iUByWIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.826 24.514)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iPe7ltd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.052 11.286)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="itBbMvd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.264 -52.014)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i1zPpnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.33 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iybtoVb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.1932 2.03299 -3.44754 -10.50243 19.399 10.155)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i1L6kIR" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.061 7.69)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="fwhs_rbtx"/><stop offset=".979" class="zm52n4iau"/></radialGradient><radialGradient id="iL03lyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 1.625 0 18.206 9.5)" gradientUnits="userSpaceOnUse"><stop class="pny-5j48c"/><stop offset="1" class="tkjjbs8fr"/></radialGradient><radialGradient id="i6OETuD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39844 1.40625 0 14.002 9.774)" gradientUnits="userSpaceOnUse"><stop class="gxqvevvli"/><stop offset="1" class="ivyjsibqp"/></radialGradient><radialGradient id="izQzJJe" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 -.6875 2.02145 .8729 15.182 14.101)" gradientUnits="userSpaceOnUse"><stop class="uj2dsybcg"/><stop offset="1" class="lqle2ww0r"/></radialGradient><radialGradient id="iCQg0te" cx="0" cy="0" r="1" gradientTransform="matrix(-.66772 -2.3456 1.34205 -.38204 16.852 11.9)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="ihZ1b6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.199 10.045)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijRE5Kb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.465 .664)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNwj34d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.935 10.045)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iYyosWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.649 10.264)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ia8q6hd" width="20.537" height="10.328" x="5.535" y="4.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1799" result="effect2_innerShadow_4002_1799"/></filter><filter id="iJUQ5qd" width="9.49" height="10.956" x="14.088" y="6.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.509804 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iVGzzzb" width="5.894" height="10.985" x="8.629" y="6.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.466667 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iDdpyRd" width="8" height="6.44" x="12.053" y="15.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="il03aYd" width="8.45" height="4.612" x="11.784" y="25.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".125"/></filter><filter id="iIuzK7b" width="8.05" height="4.28" x="11.934" y="25.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="i9v2kDe" width="4.618" height="5.556" x="23.508" y="24.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iFPv1ee" width="2.047" height=".25" x="23.903" y="25.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="ivmLbUx" width="2.047" height=".25" x="23.825" y="27.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="iOSLOxc" width="2.047" height=".25" x="23.903" y="28.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="iNcQnab" width="3.318" height="3.218" x="9.701" y="9.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iNTNF9b" width="3.218" height="3.468" x="19.231" y="8.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="ia5N2tb" width="3.148" height="3.148" x="19.266" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".25"/></filter><filter id="iCYpDjd" width="2.648" height="2.648" x="10.005" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".125"/></filter><filter id="i2cCo1b" width="10.325" height="9.709" x="11.149" y="6.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="i8byDCe" width="3.685" height="1.517" x="14.226" y="12.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="iLa346G" width="2.797" height="3.568" x="14.476" y="9.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".25"/></filter><filter id="ieMajkm" width="2.297" height="3.068" x="14.953" y="9.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".125"/></filter><filter id="iVQJoBc" width="2.447" height="1.069" x="12.302" y="7.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="inMrSUb" width="2.437" height="1.059" x="17.628" y="7.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iK4YTBb" width="3.001" height="1.285" x="16.959" y="9.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="igh1ONe" width="3.001" height="1.285" x="12.174" y="9.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/></filter><filter id="iLFb70N" width=".786" height=".696" x="17.464" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="iKTw8RE" width=".891" height=".913" x="18.304" y="9.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".1"/></filter><filter id="igb4j6d" width=".986" height="1.04" x="13.962" y="9.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".1"/></filter><filter id="iP0UhLj" width=".912" height=".704" x="13.207" y="9.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".05"/></filter><filter id="ikXhIgd" width="2.332" height=".95" x="17.614" y="7.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".1"/></filter><filter id="ijmy1Tb" width="2.332" height=".95" x="12.068" y="7.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1799" stdDeviation=".1"/></filter><filter id="iXsO9Nc" width="7.625" height="9.853" x="21.907" y="10.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.490196 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1799"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.788235 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1799" result="effect2_innerShadow_4002_1799"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.552941 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1799" result="effect3_innerShadow_4002_1799"/></filter><linearGradient id="iuAtIYK" x1="15.973" x2="15.973" y1="3.951" y2="4.004" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="innoTqb" x1="16.054" x2="16.054" y1="4.75" y2="14.781" gradientUnits="userSpaceOnUse"><stop class="ht4fz-b9x"/><stop offset="1" class="rk4knin1y"/></linearGradient><linearGradient id="iQwF04c" x1="11.576" x2="11.576" y1="6.937" y2="17.672" gradientUnits="userSpaceOnUse"><stop class="v_sk-gbvv"/><stop offset="1" class="c4n8i1bmu"/></linearGradient><linearGradient id="ix0RxQc" x1="8.994" x2="5.403" y1="28.375" y2="28.375" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iY8MVRc" x1="26.556" x2="23.014" y1="22.805" y2="29.111" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iukFimd" x1="20.053" x2="19.119" y1="18.438" y2="18.438" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iguY2zp" x1="12.053" x2="12.387" y1="18.438" y2="18.438" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iy3IF4c" x1="17.216" x2="16.003" y1="29.062" y2="21.937" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iqkZAkb" x1="23.067" x2="22.841" y1="29.594" y2="29.594" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="inevGhd" x1="8.994" x2="9.118" y1="29.594" y2="29.594" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iaKCIve" x1="13.841" x2="20.372" y1="28.281" y2="28.281" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="i0gbhpl" x1="25.664" x2="25.664" y1="21.531" y2="24.711" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iuKjv6b" x1="25.692" x2="25.692" y1="22.234" y2="21.641" gradientUnits="userSpaceOnUse"><stop class="tun7z-ngg"/><stop offset="1" class="z3nh0_7nl"/></linearGradient><linearGradient id="irbU6sb" x1="27.536" x2="23.508" y1="27.983" y2="27.983" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iY4kJQe" x1="25.709" x2="23.873" y1="25.898" y2="25.898" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="itZIfqb" x1="25.63" x2="23.794" y1="27.203" y2="27.203" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iPUO95c" x1="25.709" x2="23.873" y1="28.508" y2="28.508" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="i8ciBVY" x1="9.701" x2="12.661" y1="10.934" y2="10.934" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="ig1fmAe" x1="17.711" x2="14.324" y1="13.422" y2="13.422" gradientUnits="userSpaceOnUse"><stop class="iazz9lb4s"/><stop offset="1" class="iazz9lb4s"/></linearGradient><linearGradient id="i9DdRyc" x1="16.101" x2="16.101" y1="12.647" y2="10.079" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ifawxge" x1="15.1" x2="15.917" y1="11.917" y2="12.017" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="i5Lm3qc" x1="16.101" x2="16.101" y1="12.735" y2="12.151" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ioGF3Yv" x1="18.976" x2="18.663" y1="10.099" y2="10.292" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiheKZd" x1="14.679" x2="14.365" y1="10.098" y2="10.292" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a39moy9vg {
  stop-color: var(--svg-color--ffd636, #FFD636);
}

.a77_r14cc {
  fill: var(--svg-color--000, #000);
  d: path("M14.444 10.46a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.a97twobia {
  d: path("M23.508 25.246c0-.401.325-.732.727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.ap8mygb2m {
  stop-color: var(--svg-color--cf9826, #CF9826);
}

.arzh1b1yk {
  d: path("M16.89 7.954c-1.716 0-2.526-.732-2.802-1.098c.836.027 2.457 0 4.584 0c2.659 0 4.35 1.047 4.703 2.97c.257 1.647-.242 2.69-.12 3.173c.12.483.563 1.762-.283 3.011c-.677 1-2.108 1.551-2.739 1.702h-2.185V15.86c2.366-.725 2.319-3.001 2.37-3.212c.05-.212.421-1.941.297-3.337c-.096-1.073-.788-1.326-1.299-1.302c-.204 0-1.004-.054-2.526-.054");
}

.ato4pubwa {
  d: path("m16.904 19.63l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.aum_h2loy {
  stop-color: var(--svg-color--9a6904, #9A6904);
}

.b1-s7bbow {
  d: path("m10.154 5.49l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.bauqsdjhx {
  d: path("M16.069 13.5a3.1 3.1 0 0 1-1.415-.336c-.135-.077-.29.086-.203.221c.347.53.934.876 1.618.876c.683 0 1.27-.346 1.617-.876c.087-.135-.067-.289-.202-.221a3.1 3.1 0 0 1-1.415.337");
}

.bdkg68dwh {
  d: path("M10.555 7.49c.977-.498 2.222-.543 2.649-.553l-.514 4.652l1.833 4.33l-2.608 1.753c-3.585-.735-3.348-3.564-3.137-4.356c.221-.83.028-1.02-.086-1.787c-.272-1.833.329-3.256 1.863-4.039");
}

.bewxvkb0d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.028 25.898h1.797");
}

.bk9jifp6c {
  d: path("M23.014 29.92V17.95h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.bnge9kbad {
  stop-color: var(--svg-color--9a6904, #9A6904);
  stop-opacity: 0;
}

.c14r1779w {
  stop-color: var(--svg-color--ca6202, #CA6202);
}

.c2bt_obzp {
  d: path("m15.728 10.347l-.5 1.626a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.626c-.135-.357-.645-.357-.751 0");
}

.c4n8i1bmu {
  stop-color: var(--svg-color--d67a1d, #D67A1D);
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.chk8ftbiu {
  d: path("M19.397 7.939H16.78c-1.38 0-2.045-.56-2.629-1.083c0 0-.86.041-1.258.1c-.215.235-.444.532-.977.887c-.231.115-.756.526-.766 1.46l.064 2.593c.106 2.802 2.262 4.67 4.88 4.67c2.619 0 4.765-1.868 4.88-4.67V9.394c0-1.34-1.393-1.455-1.576-1.455");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpgq_pqip {
  d: path("M11.617 4.75c-.849.031-2.678.229-4.102 1.336c-1.237.962-1.476 2.117-1.476 3.086v.476c-.094 1.782 1.445 4.93 6.883 4.93h6.263c5.438 0 6.977-3.148 6.883-4.93v-.476c0-.969-.239-2.124-1.476-3.086c-1.424-1.107-3.253-1.305-4.102-1.336z");
}

.d6569kbrr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.95 27.203h1.797");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.d81p1wr-c {
  d: path("M15.984 18.61c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.d8ju_4bds {
  cx: 13.664px;
  cy: 9.949px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.d9opa32qi {
  d: path("M24.93 19.93h1.524v1.734a.25.25 0 0 1-.25.25H25.18a.25.25 0 0 1-.25-.25z");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dhw5gpb4u {
  fill: var(--svg-color--c7b3db, #C7B3DB);
  d: path("M22.809 10.984a.6.6 0 0 0-.602.602v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 1 1-1.758 0v-4.45a.6.6 0 0 0-.602-.602");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e5h9sobbm {
  d: path("M20.84 12.456a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.ewu9b2erc {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.984 15.44c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.ez9415bai {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.726 9.296c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.ffx6-fbot {
  stop-color: var(--svg-color--ffca28, #FFCA28);
}

.fk-65dr-t {
  stop-color: var(--svg-color--ffca2c, #FFCA2C);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fsxgh2bro {
  stop-color: var(--svg-color--ca9e18, #CA9E18);
}

.ft5dv1b6b {
  fill: none;
}

.fwhs_rbtx {
  stop-color: var(--svg-color--ef9939, #EF9939);
  stop-opacity: 0;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g5fb-ccku {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.069 13.5a3.1 3.1 0 0 1-1.415-.336c-.135-.077-.29.086-.203.221c.347.53.934.876 1.618.876c.683 0 1.27-.346 1.617-.876c.087-.135-.067-.289-.202-.221a3.1 3.1 0 0 1-1.415.337Z");
}

.gde04ac1w {
  d: path("M26.167 21.71h-1v3h1z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gr2susb2n {
  stop-color: var(--svg-color--947ca9, #947CA9);
  stop-opacity: 0;
}

.gxqvevvli {
  stop-color: var(--svg-color--f69831, #F69831);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h2xkk3unb {
  d: path("M11.31 12.456a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hq-de1bfv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.028 28.508h1.797");
}

.ht4fz-b9x {
  stop-color: var(--svg-color--6a3d3e, #6A3D3E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ih9j6q0se {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.159 10.073c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.369c.269.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.08-.45");
}

.it6vkhr5x {
  cx: 13.664px;
  cy: 9.949px;
  rx: 0.389px;
  ry: 0.197px;
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.ivyjsibqp {
  stop-color: var(--svg-color--f69831, #F69831);
  stop-opacity: 0;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_fcs3b5z {
  d: path("M20.84 11.92a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j6p88_eog {
  d: path("M15.984 15.44c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.jkqn4jkjg {
  d: path("M18.135 9.757c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.k9ocfpb1k {
  stop-color: var(--svg-color--e78b0c, #E78B0C);
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kfh4csf0n {
  stop-color: var(--svg-color--e78b0c, #E78B0C);
  stop-opacity: 0;
}

.kj38e6byz {
  stop-color: var(--svg-color--ffd636, #FFD636);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.l3_73ztho {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.135 9.757c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.l5iilfaqn {
  d: path("M26.826 23.06c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.la8uztbfo {
  stop-color: var(--svg-color--7c4e03, #7C4E03);
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkb_c2bpv {
  d: path("M23.014 17.98c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41V16.6c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.lpz5gxbuh {
  d: path("M14.748 10.355c0-.288-.234-.48-.297-.538l-.289.278l.178.361z");
}

.lqle2ww0r {
  stop-color: var(--svg-color--fca933, #FCA933);
  stop-opacity: 0;
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lxps010rs {
  stop-color: var(--svg-color--d77220, #D77220);
  stop-opacity: 0;
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m06r6xc-d {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("M19.607 8.816a.24.24 0 0 1-.135-.038c-.01 0-.731-.414-1.53-.26a.26.26 0 0 1-.308-.212a.26.26 0 0 1 .211-.308c.992-.183 1.858.308 1.887.327c.125.077.174.24.096.366a.24.24 0 0 1-.221.125");
}

.m251pe56x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.408 9.296c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mvc3mwbbx {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("M12.57 8.816a.26.26 0 0 1-.23-.135a.27.27 0 0 1 .095-.366c.039-.019.896-.51 1.897-.327c.144.029.24.164.212.308c-.03.154-.164.25-.308.221c-.809-.144-1.531.26-1.531.26a.24.24 0 0 1-.135.039");
}

.n-dwk955l {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.84 11.92a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.nb-_v43xz {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
  stop-opacity: 0;
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.ngmd0gjho {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.33 11.92a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.nsx0lpbbb {
  d: path("M19.397 7.939H16.78c-1.38 0-2.045-.56-2.629-1.083c0 0-.927.041-1.258.1c-.215.235-.444.532-.977.887c-.231.115-.756.526-.766 1.46l.064 2.593c.106 2.802 2.262 4.67 4.88 4.67c2.619 0 4.765-1.868 4.88-4.67V9.394c0-1.34-1.393-1.455-1.576-1.455");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.oaz1a_a-z {
  d: path("M18.995 10.343a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.obyiy1bpq {
  fill: var(--svg-color--000, #000);
  d: path("M17.69 10.46c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.ox-9gcclq {
  stop-color: var(--svg-color--ca6202, #CA6202);
  stop-opacity: 0;
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn0-kabdz {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("M15.5 10.573L15 12.2a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.134-.356-.645-.356-.75 0");
}

.pny-5j48c {
  stop-color: var(--svg-color--ffbd31, #FFBD31);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.py0vwh06s {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.474 25.75h-6.94c-.28 0-.5.217-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.q0pd27b8f {
  d: path("m13.018 21.414l3.035-2.123l2.988 2.084c.42.324 1.012.465 1.012-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.595.823.964.563");
}

.qayu9abrk {
  stop-color: var(--svg-color--cf9826, #CF9826);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rht-9g91b {
  stop-color: var(--svg-color--ffd740, #FFD740);
}

.rk4knin1y {
  stop-color: var(--svg-color--6e4e4c, #6E4E4C);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.slp9rv7dh {
  stop-color: var(--svg-color--ffc832, #FFC832);
  stop-opacity: 0;
}

.sxqibbcpg {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.976 10.073c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.073.369c-.268.217-.232.495-.024.6l.556.317c.652-.211 1.372-.24 2.079-.45");
}

.sy9dxtbsi {
  d: path("M13.933 9.568a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.t-hnzv4je {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.914 8.2c.237-.1 1.324 0 1.732.312");
}

.t5w61l-jh {
  d: path("M18.2 9.568a.893.893 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.tkjjbs8fr {
  stop-color: var(--svg-color--ffbd31, #FFBD31);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tun7z-ngg {
  stop-color: var(--svg-color--9e83be, #9E83BE);
}

.ugwoxpb1x {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
}

.uj2dsybcg {
  stop-color: var(--svg-color--fca933, #FCA933);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v_sk-gbvv {
  stop-color: var(--svg-color--ffa02c, #FFA02C);
}

.v5c1nslii {
  d: path("M19.474 25.75h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vnxqexb9a {
  stop-color: var(--svg-color--947ca9, #947CA9);
}

.vooh3tegw {
  stop-color: var(--svg-color--cd8a31, #CD8A31);
}

.vpvk9xb4p {
  stop-color: var(--svg-color--d08d1f, #D08D1F);
  stop-opacity: 0;
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vvmps0bsz {
  stop-color: var(--svg-color--ffca28, #FFCA28);
  stop-opacity: 0;
}

.vwnwx2byo {
  stop-color: var(--svg-color--d2c4e1, #D2C4E1);
}

.vzaknebes {
  stop-color: var(--svg-color--b198c9, #B198C9);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w1rvhsi1q {
  d: path("M21.974 5.85h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.w94zsfoim {
  stop-color: var(--svg-color--f99e1e, #F99E1E);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wjcc8nbvz {
  stop-color: var(--svg-color--9b860a, #9B860A);
}

.wjkbrmbdg {
  stop-color: var(--svg-color--d08d1f, #D08D1F);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.x03fshbgn {
  stop-color: var(--svg-color--9b860a, #9B860A);
  stop-opacity: 0;
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xlyybr0fb {
  stop-color: var(--svg-color--c6912a, #C6912A);
}

.xykughmpx {
  stop-color: var(--svg-color--ffc832, #FFC832);
}

.y_g2abcid {
  d: path("M8.994 29.92V17.95h-.007a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yidy664bk {
  stop-color: var(--svg-color--c88714, #C88714);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.z07lf2bwe {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.1 8.2c-.237-.1-1.324 0-1.732.312");
}

.z3nh0_7nl {
  stop-color: var(--svg-color--9e83be, #9E83BE);
  stop-opacity: 0;
}

.z9g4t4ltr {
  d: path("M11.33 11.92a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zm52n4iau {
  stop-color: var(--svg-color--c5801e, #C5801E);
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
