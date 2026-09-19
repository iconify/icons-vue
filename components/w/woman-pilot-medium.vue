<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#id4Rwoe)"><path fill="url(#iz1a2ub)" class="x5lq-cb1m"/><path fill="url(#i2nqYvc)" class="x5lq-cb1m"/><path fill="url(#iFWWZ5d)" class="x5lq-cb1m"/><path fill="url(#itUShcb)" class="x5lq-cb1m"/></g><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="umfrftwnu"/><path fill="url(#iqdGPbc)" class="umfrftwnu"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#iio66pd)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#iNShuxC)"><path class="zvdkucbqp"/></g><g filter="url(#iBQfLwe)"><path fill="url(#iMm4Ddd)" class="u0ana6wkh"/><path fill="url(#ideVytc)" class="u0ana6wkh"/><path fill="url(#iNjTTxJ)" class="u0ana6wkh"/></g><path fill="url(#iI9K8nc)" class="u0ana6wkh"/><g filter="url(#iAM7OyH)"><path class="gdlbulygy"/></g><g filter="url(#i6yb4Cc)"><path fill="url(#itFU7Nd)" class="wd-dmob4h"/><path fill="url(#iXl3B5d)" class="wd-dmob4h"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#iQwoj1d)" class="gael-ox4b"/><g filter="url(#ieeikpc)"><path fill="url(#iMNODVc)" class="v6z_k_d_d"/></g><path fill="url(#i3IxZud)" class="zpz9k1skg"/><path fill="url(#ird5KWc)" class="zpz9k1skg"/><path fill="url(#imA9y9d)" class="zpz9k1skg"/><g filter="url(#i8gkFWb)"><path fill="url(#irvKidb)" class="dwn0mabie"/></g><path fill="url(#isjj1Ed)" class="dwn0mabie"/><g filter="url(#ikomfOd)"><path fill="url(#itJY7Sq)" class="p7nf3ob8n"/><path fill="url(#ijNhxcH)" class="p7nf3ob8n"/></g><g filter="url(#icCUIge)"><path class="deojuhb5n"/><path fill="url(#imDPrXo)" class="x36oj-bei"/></g><g filter="url(#iwuAKQd)"><path class="h8w62nq_b"/><path fill="url(#iuJQyjd)" class="w1q4p_brz"/></g><g filter="url(#iuFTJgb)"><path fill="url(#iRvAS7M)" class="yku-jjbxm"/><path fill="url(#i51rLSb)" class="yku-jjbxm"/><path fill="url(#iMpefsS)" class="yku-jjbxm"/><path fill="url(#iRgU7Db)" class="yku-jjbxm"/><path fill="url(#iJBLWBd)" class="yku-jjbxm"/><path fill="url(#ivzdOFc)" class="yku-jjbxm"/><path fill="url(#iYhNCMd)" class="yku-jjbxm"/><path fill="url(#ime84Pb)" class="yku-jjbxm"/></g><path fill="url(#iuWv93b)" class="yku-jjbxm"/><path fill="url(#iJJhxjt)" class="yku-jjbxm"/><g filter="url(#i5b7MAd)"><path class="ksb9exb2e"/></g><g filter="url(#ihI2fKe)"><path class="ppxs_0mvd"/><path fill="url(#i427B5d)" class="jgxw3bwkd"/><path fill="url(#i0AdzYT)" class="jgxw3bwkd"/><path fill="url(#i1Sve5d)" class="jgxw3bwkd"/><path fill="url(#iuA2hye)" class="jgxw3bwkd"/><path fill="url(#iTBD1se)" class="jgxw3bwkd"/></g><g filter="url(#iBO2TIe)"><path stroke="url(#icyOcJe)" class="egewjuzea"/></g><path class="zbk9t7bxo"/><g filter="url(#i5iYiha)"><path class="plmvbicic"/></g><g filter="url(#it2bKde)"><path class="on88mac4w"/></g><path class="ej7lkn__p"/><path fill="url(#iPb4JXb)" class="lc25_sb8l"/><path class="xb5ko4bzo"/><g filter="url(#iWGrN1c)"><path class="ec24qxbim"/><path fill="url(#ijJ6Lhs)" class="kz8pytb-n"/></g><g filter="url(#id45Lvc)"><path fill="url(#iNTYZzA)" class="lqiqpkb-y"/></g><path class="l0ug9sc6z"/><path fill="url(#i9H8cWb)" class="ngvf-_uyg"/><path class="pqw4-acyx"/><g filter="url(#iPogxWd)"><path fill="url(#i3ld8pc)" class="wrbuglber"/></g><g filter="url(#iII6gvb)"><ellipse transform="rotate(-27.914 13.452 10.14)" class="mw25lsb-r"/><ellipse fill="url(#iN474Md)" transform="rotate(-27.914 13.452 10.14)" class="hi8ikbqul"/></g><g filter="url(#iWlt3bA)"><path class="od16rgzdk"/></g><g filter="url(#it1pprb)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#iicy1hu)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iRzB4mc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#iotGiwe)"><path class="ho8k-2bnl"/></g><g filter="url(#iVFMnDd)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#iz2Kaec)"><path fill="url(#iYqfV7X)" class="hdde0uvpo"/></g><g filter="url(#isnhxCb)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="i2nqYvc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00674 2.15053 -.65628 -.6124 10.563 7.262)" gradientUnits="userSpaceOnUse"><stop class="jx1glvxbe"/><stop offset="1" class="zv6-xlm2f"/></radialGradient><radialGradient id="iFWWZ5d" cx="0" cy="0" r="1" gradientTransform="matrix(2.00831 2.5469 -.95279 .7513 21.693 7.116)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="eser-fblc"/><stop offset="1" class="v41ltixcj"/></radialGradient><radialGradient id="itUShcb" cx="0" cy="0" r="1" gradientTransform="rotate(74.476 3.123 22.178)scale(1.7514 .96919)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="x4bent11b"/><stop offset="1" class="o36zcrb8j"/></radialGradient><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="iXl3B5d" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.867)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iQwoj1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.60937 -.56235 .41494 19.375 17.468)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="p96-cobfo"/><stop offset="1" class="t_e0v9wgf"/></radialGradient><radialGradient id="i3IxZud" cx="0" cy="0" r="1" gradientTransform="rotate(89.999 -.228 16.205)scale(1.6196 2.56357)" gradientUnits="userSpaceOnUse"><stop class="tr8p2emnq"/><stop offset=".65" class="ud339rbez"/></radialGradient><radialGradient id="ird5KWc" cx="0" cy="0" r="1" gradientTransform="rotate(151.477 6.596 10.465)scale(3.05485 4.36004)" gradientUnits="userSpaceOnUse"><stop offset=".366" class="d77sc8bqo"/><stop offset="1" class="un81c3j7o"/></radialGradient><radialGradient id="imA9y9d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51708 1.48792 -.48563 -.49515 18.09 16.218)" gradientUnits="userSpaceOnUse"><stop class="nquyfbcpc"/><stop offset="1" class="jvmh7tubh"/></radialGradient><radialGradient id="isjj1Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.827 12.443)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="itJY7Sq" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.945 11.273)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ijNhxcH" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.85 9.127)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="imDPrXo" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.297 10.946)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iuJQyjd" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.652 5.417)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iRvAS7M" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.253 7.207)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i51rLSb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.766 7.455)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iMpefsS" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.744 16.803)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iRgU7Db" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.19798 -8.99739 0 15.906 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="zzcde0rmw"/><stop offset="1" class="prhvrsmyy"/></radialGradient><radialGradient id="iJBLWBd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.7829 1.18161 -2.03436 -11.67803 17.716 12.027)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="ivzdOFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.207 9.877)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iYhNCMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.83 9.649)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="ime84Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.289 7.562)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iuWv93b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -10.4477 21.001 11.365)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iJJhxjt" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53448 -5.40572 0 15.462 7.923)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="yly6gct9e"/><stop offset="1" class="xysm54rvi"/></radialGradient><radialGradient id="i427B5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.69 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iuA2hye" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.45 12.303)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iPb4JXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.088 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijJ6Lhs" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.86 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9H8cWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.723 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iN474Md" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.865 -1.386)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="id4Rwoe" width="15.646" height="10.422" x="8.153" y="6.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.239216 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.309804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2465" result="effect2_innerShadow_4002_2465"/></filter><filter id="iio66pd" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".5"/></filter><filter id="iNShuxC" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".5"/></filter><filter id="iBQfLwe" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2465" result="effect2_innerShadow_4002_2465"/></filter><filter id="iAM7OyH" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".5"/></filter><filter id="i6yb4Cc" width="3.042" height="14.156" x="18.465" y="15.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2465" result="effect2_innerShadow_4002_2465"/></filter><filter id="ieeikpc" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2465" result="effect2_innerShadow_4002_2465"/></filter><filter id="i8gkFWb" width="3.368" height="3.218" x="9.611" y="9.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="ikomfOd" width="3.218" height="3.468" x="19.124" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="icCUIge" width="3.148" height="3.148" x="19.159" y="9.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".25"/></filter><filter id="iwuAKQd" width="2.848" height="2.848" x="9.815" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".175"/></filter><filter id="iuFTJgb" width="10.191" height="11.127" x="10.81" y="5.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="i5b7MAd" width="2.877" height="3.682" x="14.305" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".25"/></filter><filter id="ihI2fKe" width="2.377" height="3.182" x="14.717" y="9.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".125"/></filter><filter id="iBO2TIe" width="3.702" height="1.526" x="14.054" y="13.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".05"/></filter><filter id="i5iYiha" width="3.001" height="1.285" x="16.848" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="it2bKde" width="3.001" height="1.285" x="11.962" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="iWGrN1c" width=".787" height=".696" x="17.353" y="9.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".05"/></filter><filter id="id45Lvc" width=".891" height=".913" x="18.193" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".1"/></filter><filter id="iPogxWd" width=".986" height="1.04" x="13.75" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".1"/></filter><filter id="iII6gvb" width=".913" height=".704" x="12.996" y="9.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".05"/></filter><filter id="iWlt3bA" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".1"/></filter><filter id="it1pprb" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2465" result="effect2_innerShadow_4002_2465"/></filter><filter id="iicy1hu" width="10.9" height="2.77" x="10.555" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="iotGiwe" width="4.831" height="2.64" x="13.59" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2465" stdDeviation=".125"/></filter><filter id="iVFMnDd" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="iz2Kaec" width="2.298" height="1.22" x="15.943" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><filter id="isnhxCb" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2465"/></filter><linearGradient id="iz1a2ub" x1="20.861" x2="15.976" y1="7.962" y2="17.129" gradientUnits="userSpaceOnUse"><stop class="cviq8bj5e"/><stop offset="1" class="v3tp131zi"/></linearGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iI9K8nc" x1="13.295" x2="13.295" y1="29.69" y2="23.357" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="irvKidb" x1="9.611" x2="11.468" y1="10.921" y2="10.921" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i0AdzYT" x1="14.967" x2="15.906" y1="12.165" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i1Sve5d" x1="15.906" x2="15.906" y1="12.872" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iTBD1se" x1="15.906" x2="15.906" y1="10.19" y2="10.671" gradientUnits="userSpaceOnUse"><stop class="lsm33z00a"/><stop offset="1" class="mijxpbc3a"/></linearGradient><linearGradient id="icyOcJe" x1="14.841" x2="15.302" y1="14.373" y2="13.661" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iNTYZzA" x1="18.866" x2="18.552" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3ld8pc" x1="14.467" x2="14.153" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iRzB4mc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset=".875" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYqfV7X" x1="18.083" x2="16.597" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pilot-medium" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
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

.cviq8bj5e {
  stop-color: var(--svg-color--4c2d34, #4C2D34);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d77sc8bqo {
  stop-color: var(--svg-color--87515f, #87515F);
  stop-opacity: 0;
}

.deojuhb5n {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dwn0mabie {
  d: path("M11.22 12.443a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.ec24qxbim {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.024 9.948c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.egewjuzea {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.ej7lkn__p {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.297 9.488c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.231a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.372-1.127");
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.ft5dv1b6b {
  fill: none;
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gdlbulygy {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.48l.444 1.049c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.507.174.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h8w62nq_b {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
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

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
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

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
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

.jvmh7tubh {
  stop-color: var(--svg-color--9e706d, #9E706D);
  stop-opacity: 0;
}

.jx1glvxbe {
  stop-color: var(--svg-color--594542, #594542);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
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

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksb9exb2e {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.513 10.61l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.493-.376-.612 0");
}

.kz8pytb-n {
  d: path("M18.024 9.948c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.l0ug9sc6z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.515 9.488c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
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

.lsm33z00a {
  stop-color: var(--svg-color--a17370, #A17370);
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mijxpbc3a {
  stop-color: var(--svg-color--a17370, #A17370);
  stop-opacity: 0;
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
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

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.ngvf-_uyg {
  d: path("M13.721 9.76a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nquyfbcpc {
  stop-color: var(--svg-color--9e706d, #9E706D);
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o36zcrb8j {
  stop-color: var(--svg-color--524140, #524140);
  stop-opacity: 0;
}

.od16rgzdk {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.329h-.592c-.124 0-.23.09-.239.22c-.01.129.096.248.22.248h.152c.18 0 .18.08.213.15c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.218l.086-.2c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.249-.238-.249");
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

.on88mac4w {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.764 10.265c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.6l.556.316c.652-.21 1.372-.239 2.079-.45");
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
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

.plmvbicic {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.048 10.265c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.024.6l-.556.316c-.652-.21-1.372-.239-2.078-.45");
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.ppxs_0mvd {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.523 10.472l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.pqw4-acyx {
  fill: var(--svg-color--000, #000);
  d: path("M14.233 10.652a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.prhvrsmyy {
  stop-color: var(--svg-color--954f80, #954F80);
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

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t_e0v9wgf {
  stop-color: var(--svg-color--69646e, #69646E);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.tr8p2emnq {
  stop-color: var(--svg-color--934f74, #934F74);
}

.u0ana6wkh {
  d: path("M13.295 15.837q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.ud339rbez {
  stop-color: var(--svg-color--a56c7b, #A56C7B);
}

.umfrftwnu {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.377");
}

.un81c3j7o {
  stop-color: var(--svg-color--87515f, #87515F);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v3tp131zi {
  stop-color: var(--svg-color--2f0e31, #2F0E31);
}

.v41ltixcj {
  stop-color: var(--svg-color--675250, #675250);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v6z_k_d_d {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.141z");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1q4p_brz {
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
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

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wrbuglber {
  d: path("M14.537 10.547c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.x36oj-bei {
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.x4bent11b {
  stop-color: var(--svg-color--524140, #524140);
}

.x5lq-cb1m {
  d: path("M10.636 6.706h10.68c.092.577.528.994.98 1.425c.285.273.577.553.792.882c.625.958.461 1.953.176 2.937c-.076.264-.072.494 0 .637c.133.32.285.785.285 1.296a3.24 3.24 0 0 1-3.246 3.246H11.65a3.24 3.24 0 0 1-3.246-3.246c0-.51.153-.976.286-1.296c.071-.143.055-.445 0-.637c-.286-.984-.45-1.979.176-2.937c.214-.33.506-.609.792-.882c.452-.431.888-.848.98-1.425");
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xb5ko4bzo {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.652a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.xysm54rvi {
  stop-color: var(--svg-color--7a4b5a, #7A4B5A);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yku-jjbxm {
  d: path("M10.818 9.57h.013l-.01-.264l-.01-.307c.02-.948.573-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.193a.264.264 0 0 1 .46-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.684-4.983 4.684s-4.86-1.881-4.983-4.684z");
}

.yly6gct9e {
  stop-color: var(--svg-color--7a4b5a, #7A4B5A);
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.zbk9t7bxo {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zpz9k1skg {
  d: path("M15.976 18.503c1.79-.788 1.932-1.316 1.92-1.7v-.99h-3.839v.99c-.013.384.224.97 1.92 1.7");
}

.zv6-xlm2f {
  stop-color: var(--svg-color--594542, #594542);
  stop-opacity: 0;
}

.zvdkucbqp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.271c-.54.783-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.zzcde0rmw {
  stop-color: var(--svg-color--a0637b, #A0637B);
  stop-opacity: 0;
}

</style>
