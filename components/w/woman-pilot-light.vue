<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iaX58SM)"><path fill="url(#iKhXjzM)" class="udeghrbqj"/><path fill="url(#iDKV0tc)" class="udeghrbqj"/><path fill="url(#iSc9Wvd)" class="udeghrbqj"/><path fill="url(#i01fBxe)" class="udeghrbqj"/></g><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="umfrftwnu"/><path fill="url(#iqdGPbc)" class="umfrftwnu"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#iN2OBvd)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#inK3TRd)"><path class="ouoob-ulp"/></g><g filter="url(#iINN7sc)"><path fill="url(#iMm4Ddd)" class="d8vxffbru"/><path fill="url(#ideVytc)" class="d8vxffbru"/><path fill="url(#iNjTTxJ)" class="d8vxffbru"/></g><path fill="url(#iXFEZTd)" class="d8vxffbru"/><g filter="url(#iyDWbjb)"><path class="n7k0g1b5l"/></g><g filter="url(#ilzb8oS)"><path fill="url(#itFU7Nd)" class="wd-dmob4h"/><path fill="url(#iXl3B5d)" class="wd-dmob4h"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#iQwoj1d)" class="gael-ox4b"/><g filter="url(#iW8sATd)"><path fill="url(#iMNODVc)" class="v6z_k_d_d"/></g><path fill="url(#iiiIoac)" class="zpz9k1skg"/><path fill="url(#ieJzcTb)" class="zpz9k1skg"/><path fill="url(#ia3hwQe)" class="zpz9k1skg"/><g filter="url(#iWa8lRc)"><path fill="url(#iYuMUvd)" class="dwn0mabie"/></g><g filter="url(#iEvvUPe)"><path fill="url(#iq23b1c)" class="p7nf3ob8n"/><path fill="url(#iPi9tGd)" class="p7nf3ob8n"/></g><g filter="url(#icT807x)"><path class="iaxhzvbst"/><path fill="url(#iXDrupd)" class="x36oj-bei"/></g><g filter="url(#izBh9Yb)"><path class="ecz_w1buy"/><path fill="url(#i1rKLbo)" class="w1q4p_brz"/></g><g filter="url(#iFyO0Hb)"><path fill="url(#iHHTxTd)" class="yku-jjbxm"/><path fill="url(#idfZfLc)" class="yku-jjbxm"/><path fill="url(#i5iFQ1b)" class="yku-jjbxm"/><path fill="url(#iLsPmkc)" class="yku-jjbxm"/><path fill="url(#ibxRGfH)" class="yku-jjbxm"/><path fill="url(#i0xjYye)" class="yku-jjbxm"/><path fill="url(#iHluerb)" class="yku-jjbxm"/></g><path fill="url(#ipEu1Ed)" class="yku-jjbxm"/><path fill="url(#iHk4Gkd)" class="yku-jjbxm"/><path fill="url(#iRli2Wd)" class="yku-jjbxm"/><g filter="url(#i0ogbne)"><path class="gv13kbbuu"/></g><g filter="url(#ikndAGb)"><path fill="url(#iAkeHQe)" class="jgxw3bwkd"/><path fill="url(#iAl8M5v)" class="jgxw3bwkd"/><path fill="url(#iqJcxBc)" class="jgxw3bwkd"/><path fill="url(#iZyltqc)" class="jgxw3bwkd"/><path fill="url(#iztNeze)" class="jgxw3bwkd"/><path fill="url(#ieaTBSd)" class="jgxw3bwkd"/></g><g filter="url(#ieTxcpd)"><path stroke="url(#iXBseBd)" class="egewjuzea"/></g><path class="zbk9t7bxo"/><g filter="url(#iCbbuLe)"><path class="cg1-u7b8l"/></g><g filter="url(#inEtgNc)"><path class="shdrnccsc"/></g><path class="ej7lkn__p"/><path fill="url(#iPb4JXb)" class="lc25_sb8l"/><path class="xb5ko4bzo"/><g filter="url(#izirYDb)"><path class="x4dy-wukn"/><path fill="url(#ijJ6Lhs)" class="rhalqdbir"/></g><g filter="url(#idHeMYd)"><path fill="url(#iNTYZzA)" class="lqiqpkb-y"/></g><path class="l0ug9sc6z"/><path fill="url(#i9H8cWb)" class="ngvf-_uyg"/><path class="pqw4-acyx"/><g filter="url(#iBs8YCc)"><path fill="url(#i3ld8pc)" class="mpkqwdnyo"/></g><g filter="url(#ir2BDVc)"><ellipse transform="rotate(-27.914 13.452 10.14)" class="mw25lsb-r"/><ellipse fill="url(#iN474Md)" transform="rotate(-27.914 13.452 10.14)" class="hi8ikbqul"/></g><g filter="url(#ixv7qkJ)"><path class="kflbiccup"/></g><g filter="url(#inISKXd)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#iMUQYHc)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iRzB4mc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#iNfbxOb)"><path class="ho8k-2bnl"/></g><g filter="url(#iYD9oNb)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#i2zIshd)"><path fill="url(#iYqfV7X)" class="hdde0uvpo"/></g><g filter="url(#iYWOCod)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="iDKV0tc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49222 1.63809 -.7506 -.68376 10.563 7.261)" gradientUnits="userSpaceOnUse"><stop class="byjccxdtl"/><stop offset="1" class="eav29bbfi"/></radialGradient><radialGradient id="iSc9Wvd" cx="0" cy="0" r="1" gradientTransform="matrix(2.00833 2.54688 -.66707 .52602 21.693 7.115)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="i6xvtdb8e"/><stop offset="1" class="stq0hsb2e"/></radialGradient><radialGradient id="i01fBxe" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.6875 -.86793 .24109 23.656 13.233)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="d42me8v-p"/><stop offset="1" class="kd3kb9bpm"/></radialGradient><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="iXl3B5d" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.867)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iQwoj1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.60937 -.56235 .41494 19.375 17.468)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="p96-cobfo"/><stop offset="1" class="t_e0v9wgf"/></radialGradient><radialGradient id="iiiIoac" cx="0" cy="0" r="1" gradientTransform="rotate(89.999 -.228 16.205)scale(1.6196 2.56357)" gradientUnits="userSpaceOnUse"><stop class="dy4-cvb-g"/><stop offset=".65" class="cfh49lb8v"/></radialGradient><radialGradient id="ieJzcTb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68407 1.45873 -1.9297 -3.55068 17.39 16.51)" gradientUnits="userSpaceOnUse"><stop offset=".807" class="asnjbvp7m"/><stop offset="1" class="xsje1viod"/></radialGradient><radialGradient id="ia3hwQe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51708 1.48792 -.48563 -.49515 18.09 16.218)" gradientUnits="userSpaceOnUse"><stop class="k8fr_5sfn"/><stop offset="1" class="zaa-nr8yz"/></radialGradient><radialGradient id="iq23b1c" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.437 -16.965)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iPi9tGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 20.976 9.152)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iXDrupd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.297 10.946)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i1rKLbo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.305 10.834)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iHHTxTd" cx="0" cy="0" r="1" gradientTransform="rotate(148.465 8.609 7.392)scale(8.06619 6.83323)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset=".798" class="yhk7jqb-l"/></radialGradient><radialGradient id="idfZfLc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.157 11.658)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i5iFQ1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.526 17.625)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iLsPmkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 15.906 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="t6xsozbsb"/><stop offset=".988" class="t74523bal"/></radialGradient><radialGradient id="ibxRGfH" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.273 6.874)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i0xjYye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.207 9.877)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iHluerb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.83 9.649)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ipEu1Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.001 11.365)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iHk4Gkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.72 4.298)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iRli2Wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.37126 -6.74253 0 15.143 8.267)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="xdafxdbde"/><stop offset="1" class="bmidemtvu"/></radialGradient><radialGradient id="iAl8M5v" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.69 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iztNeze" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.45 12.303)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iPb4JXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.088 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijJ6Lhs" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.86 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9H8cWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.723 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iN474Md" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.865 -1.386)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="iaX58SM" width="15.646" height="10.422" x="8.153" y="6.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.219608 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.219608 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2471" result="effect2_innerShadow_4002_2471"/></filter><filter id="iN2OBvd" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".5"/></filter><filter id="inK3TRd" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".5"/></filter><filter id="iINN7sc" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2471" result="effect2_innerShadow_4002_2471"/></filter><filter id="iyDWbjb" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".5"/></filter><filter id="ilzb8oS" width="3.042" height="14.156" x="18.465" y="15.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2471" result="effect2_innerShadow_4002_2471"/></filter><filter id="iW8sATd" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2471" result="effect2_innerShadow_4002_2471"/></filter><filter id="iWa8lRc" width="3.368" height="3.218" x="9.611" y="9.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="iEvvUPe" width="3.218" height="3.468" x="19.124" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="icT807x" width="3.148" height="3.148" x="19.159" y="9.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".25"/></filter><filter id="izBh9Yb" width="2.948" height="2.948" x="9.765" y="9.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".2"/></filter><filter id="iFyO0Hb" width="10.191" height="11.277" x="10.81" y="5.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="i0ogbne" width="2.877" height="3.682" x="14.305" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".25"/></filter><filter id="ikndAGb" width="2.377" height="3.182" x="14.717" y="9.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".125"/></filter><filter id="ieTxcpd" width="3.702" height="1.526" x="14.054" y="13.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".05"/></filter><filter id="iCbbuLe" width="3.001" height="1.285" x="16.848" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="inEtgNc" width="3.001" height="1.285" x="11.962" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="izirYDb" width=".787" height=".696" x="17.354" y="9.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".05"/></filter><filter id="idHeMYd" width=".891" height=".913" x="18.193" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".1"/></filter><filter id="iBs8YCc" width=".986" height="1.04" x="13.75" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".1"/></filter><filter id="ir2BDVc" width=".913" height=".704" x="12.996" y="9.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".05"/></filter><filter id="ixv7qkJ" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".1"/></filter><filter id="inISKXd" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2471" result="effect2_innerShadow_4002_2471"/></filter><filter id="iMUQYHc" width="10.9" height="2.77" x="10.555" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="iNfbxOb" width="4.831" height="2.64" x="13.59" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2471" stdDeviation=".125"/></filter><filter id="iYD9oNb" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="i2zIshd" width="2.298" height="1.22" x="15.943" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><filter id="iYWOCod" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2471"/></filter><linearGradient id="iKhXjzM" x1="21.133" x2="15.976" y1="7.219" y2="17.128" gradientUnits="userSpaceOnUse"><stop class="trxz_2bws"/><stop offset="1" class="o-iy24ajy"/></linearGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iYuMUvd" x1="9.611" x2="12.57" y1="10.921" y2="10.921" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iAkeHQe" x1="14.967" x2="16.844" y1="12.338" y2="12.338" gradientUnits="userSpaceOnUse"><stop class="cgmw4sp0b"/><stop offset="1" class="o7-ddxxuo"/></linearGradient><linearGradient id="iqJcxBc" x1="14.967" x2="15.906" y1="12.165" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iZyltqc" x1="15.906" x2="15.906" y1="12.964" y2="12.353" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ieaTBSd" x1="15.906" x2="15.906" y1="10.19" y2="11.248" gradientUnits="userSpaceOnUse"><stop class="q57slp2nx"/><stop offset="1" class="smf39tzjz"/></linearGradient><linearGradient id="iXBseBd" x1="14.841" x2="15.302" y1="14.373" y2="13.661" gradientUnits="userSpaceOnUse"><stop class="zza8tc1qb"/><stop offset=".663" class="b1u8bkvdk"/></linearGradient><linearGradient id="iNTYZzA" x1="18.866" x2="18.552" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3ld8pc" x1="14.467" x2="14.153" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iRzB4mc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset=".875" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYqfV7X" x1="18.083" x2="16.597" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pilot-light" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.asnjbvp7m {
  stop-color: var(--svg-color--b57b77, #B57B77);
  stop-opacity: 0;
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b1u8bkvdk {
  stop-color: var(--svg-color--e3bdbd, #E3BDBD);
  stop-opacity: 0;
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bmidemtvu {
  stop-color: var(--svg-color--b98282, #B98282);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.byjccxdtl {
  stop-color: var(--svg-color--4e4745, #4E4745);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.cfh49lb8v {
  stop-color: var(--svg-color--ce909f, #CE909F);
}

.cg1-u7b8l {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.048 10.264c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.652-.21-1.372-.239-2.078-.45");
}

.cgmw4sp0b {
  stop-color: var(--svg-color--e5b19d, #E5B19D);
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d42me8v-p {
  stop-color: var(--svg-color--3d3a3b, #3D3A3B);
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d8vxffbru {
  d: path("M13.295 15.837q-.691.176-1.345.435l-.035.019l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dwn0mabie {
  d: path("M11.22 12.443a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.dy4-cvb-g {
  stop-color: var(--svg-color--c07d97, #C07D97);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.eav29bbfi {
  stop-color: var(--svg-color--4e4745, #4E4745);
  stop-opacity: 0;
}

.ecz_w1buy {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.egewjuzea {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.ej7lkn__p {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.297 9.488c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.231a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.372-1.127");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gv13kbbuu {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.513 10.61l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.493-.376-.612 0");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hi8ikbqul {
  cx: 13.452px;
  cy: 10.141px;
  rx: 0.39px;
  ry: 0.197px;
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.ho8k-2bnl {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.793 4.352h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.iaxhzvbst {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.jgxw3bwkd {
  d: path("m15.523 10.472l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.k8fr_5sfn {
  stop-color: var(--svg-color--cc9c9b, #CC9C9B);
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.kd3kb9bpm {
  stop-color: var(--svg-color--3d3a3b, #3D3A3B);
  stop-opacity: 0;
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kflbiccup {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.13.096.25.22.25h.152c.18 0 .18.079.213.149c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.219l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.l0ug9sc6z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.515 9.488c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc25_sb8l {
  d: path("M18.09 9.76a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.lqiqpkb-y {
  d: path("M18.885 10.534a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mpkqwdnyo {
  d: path("M14.537 10.547c0-.289-.235-.48-.298-.539l-.289.28l.178.36z");
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.mw25lsb-r {
  cx: 13.452px;
  cy: 10.141px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n7k0g1b5l {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.645l-.22-10.445l.09-.183q.507.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.ngvf-_uyg {
  d: path("M13.721 9.76a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-iy24ajy {
  stop-color: var(--svg-color--190326, #190326);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o7-ddxxuo {
  stop-color: var(--svg-color--f4c1ac, #F4C1AC);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.ouoob-ulp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.27c-.54.784-1.546 2.2-1.85 2.874c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p7nf3ob8n {
  d: path("M20.733 12.443a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.p81iumb5r {
  stop-color: var(--svg-color--6d6675, #6D6675);
}

.p96-cobfo {
  stop-color: var(--svg-color--69646e, #69646E);
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pqw4-acyx {
  fill: var(--svg-color--000, #000);
  d: path("M14.233 10.652a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.q57slp2nx {
  stop-color: var(--svg-color--d19e97, #D19E97);
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rhalqdbir {
  d: path("M18.024 9.948c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.shdrnccsc {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.764 10.264c-.266-.466-.67-.835-1.538-.835c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.372-.239 2.079-.45");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.smf39tzjz {
  stop-color: var(--svg-color--d19e97, #D19E97);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t_e0v9wgf {
  stop-color: var(--svg-color--69646e, #69646E);
  stop-opacity: 0;
}

.t6xsozbsb {
  stop-color: var(--svg-color--d294a1, #D294A1);
  stop-opacity: 0;
}

.t74523bal {
  stop-color: var(--svg-color--bb7497, #BB7497);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.trxz_2bws {
  stop-color: var(--svg-color--211622, #211622);
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.udeghrbqj {
  d: path("M10.636 6.706h10.68c.092.577.528.993.98 1.425c.285.273.577.552.792.882c.625.958.461 1.953.176 2.937c-.076.264-.072.494 0 .637c.133.32.285.785.285 1.295a3.24 3.24 0 0 1-3.246 3.246H11.65a3.24 3.24 0 0 1-3.246-3.246c0-.51.153-.975.286-1.295c.071-.143.055-.445 0-.637c-.286-.984-.45-1.979.176-2.937c.214-.33.506-.609.792-.882c.452-.432.888-.848.98-1.425");
}

.umfrftwnu {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.377");
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6z_k_d_d {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.141z");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w1q4p_brz {
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wb9snib6m {
  d: path("M21.747 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.wd-dmob4h {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V15.836l.117.032q.653.174 1.272.424l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.x36oj-bei {
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.x4dy-wukn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.024 9.948c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xb5ko4bzo {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.652a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdafxdbde {
  stop-color: var(--svg-color--b98282, #B98282);
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xsje1viod {
  stop-color: var(--svg-color--b57b77, #B57B77);
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yhk7jqb-l {
  stop-color: var(--svg-color--d7a295, #D7A295);
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.yku-jjbxm {
  d: path("M10.818 9.57h.013l-.01-.264l-.01-.307c.02-.948.573-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.193a.264.264 0 0 1 .46-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.684-4.983 4.684s-4.86-1.881-4.983-4.684z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.zaa-nr8yz {
  stop-color: var(--svg-color--cc9c9b, #CC9C9B);
  stop-opacity: 0;
}

.zbk9t7bxo {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zpz9k1skg {
  d: path("M15.976 18.503c1.79-.788 1.932-1.316 1.92-1.7v-.99h-3.839v.99c-.013.384.224.97 1.92 1.7");
}

.zza8tc1qb {
  stop-color: var(--svg-color--e3bdbd, #E3BDBD);
}

</style>
