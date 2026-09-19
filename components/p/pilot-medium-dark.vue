<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="nczmykb2q"/><path fill="url(#iqdGPbc)" class="nczmykb2q"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#inat2Ic)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#ipOtYzc)"><path class="ouoob-ulp"/></g><g filter="url(#iqilsge)"><path fill="url(#iMm4Ddd)" class="d8vxffbru"/><path fill="url(#ideVytc)" class="d8vxffbru"/><path fill="url(#iNjTTxJ)" class="d8vxffbru"/></g><path fill="url(#iXFEZTd)" class="d8vxffbru"/><g filter="url(#ibnH8Rb)"><path class="n7k0g1b5l"/></g><g filter="url(#iGBye1b)"><path fill="url(#itFU7Nd)" class="vvnobeb4d"/><path fill="url(#ipIpBme)" class="vvnobeb4d"/></g><path fill="url(#ix1PWyN)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#iqUNw9c)" class="gael-ox4b"/><path fill="url(#iDW3OSc)" class="gael-ox4b"/><g filter="url(#ixne0QG)"><path fill="url(#iMNODVc)" class="v6z_k_d_d"/></g><path fill="url(#iAnzatc)" class="l00gxpbma"/><path fill="url(#iC0i1Ne)" class="utoue4ayv"/><g filter="url(#iodpwIV)"><path fill="url(#i3G4iLd)" class="qckr5_bvx"/></g><g filter="url(#iAA1Jyz)"><path class="kflbiccup"/></g><g filter="url(#iLtfkXb)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#idEKDPc)" class="ds7rl_bqv"/><path fill="url(#i688l3c)" class="cvz-zbs5l"/><g filter="url(#iaSthnT)"><path fill="url(#ilFILib)" class="etg525soo"/><path fill="url(#i63Hz6d)" class="etg525soo"/></g><path fill="url(#irJlSKb)" class="etg525soo"/><path fill="url(#idOG2kd)" class="etg525soo"/><path fill="url(#iW4MHRY)" class="etg525soo"/><path fill="url(#io5eboc)" class="etg525soo"/><path fill="url(#iWyakRb)" class="etg525soo"/><path fill="url(#iJJpysa)" class="etg525soo"/><path fill="url(#iuVYUbb)" class="etg525soo"/><path fill="url(#i5C141b)" class="etg525soo"/><g filter="url(#ifpSSsZ)"><path class="lx4tcbb_k"/></g><g filter="url(#iALUqPO)"><path class="c-ym95agn"/><path fill="url(#i8Z4hdV)" class="fy172u3yk"/><path fill="url(#iuQsE1d)" class="fy172u3yk"/><path fill="url(#iC1HOnb)" class="fy172u3yk"/><path fill="url(#itL8p1c)" class="fy172u3yk"/><path fill="url(#i3A2C3d)" class="fy172u3yk"/></g><path fill="url(#iDT3ANJ)" class="fy172u3yk"/><path fill="url(#iBFGewe)" class="fy172u3yk"/><g filter="url(#iUeNVfY)"><path stroke="url(#ioyTlhe)" class="w5aybu7rs"/></g><path fill="url(#idDuSfV)" class="j4yxb8m0i"/><path class="hoi6qtbym"/><path fill="url(#iAI8Hfd)" class="a4fn021uw"/><path class="glm72l-sq"/><g filter="url(#iGzbWkd)"><path class="j7qzs0bmp"/><path fill="url(#i8yAhde)" class="oq2p_zbtm"/></g><g filter="url(#igEcqlB)"><path fill="url(#infS0Pe)" class="sd_er748d"/></g><path class="e8en5ebgp"/><path fill="url(#iklbSXd)" class="call61qec"/><path class="t69swbctq"/><g filter="url(#ieUBGQd)"><path fill="url(#i5uvc5u)" class="o9j-zubkj"/></g><g filter="url(#iVHMcdc)"><ellipse transform="rotate(-27.914 13.632 9.834)" class="ttv23cfgz"/><ellipse fill="url(#iZ9ggrt)" transform="rotate(-27.914 13.632 9.834)" class="zklpcnmjw"/></g><path fill="url(#iAACKkc)" class="k5tflqgkr"/><path fill="url(#i31PT2d)" class="k5tflqgkr"/><path fill="url(#iSaHKHb)" class="k5tflqgkr"/><path fill="url(#i9jEGGc)" class="k5tflqgkr"/><path fill="url(#i8FgrNb)" class="thyaubczg"/><path fill="url(#i8mj8Pe)" class="thyaubczg"/><g filter="url(#ih5YONe)"><path fill="url(#iA2Dtpv)" class="wa_uxbcpj"/></g><g filter="url(#iEpdB2c)"><path fill="url(#iLYSsTc)" class="s7h2pnz4x"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#iB1aPhb)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iJIPMLc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#idNmDme)"><path class="d-rslkbmf"/></g><g filter="url(#ivXemTc)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#i79LSxR)"><path fill="url(#iYqfV7X)" class="hdde0uvpo"/></g><g filter="url(#iViYK0d)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="ix1PWyN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="dsfnryq2l"/><stop offset="1" class="e3skdu--u"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iC0i1Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.26776 2.32112 -.79999 -.09229 21.85 7.27)" gradientUnits="userSpaceOnUse"><stop class="g0nms2b_d"/><stop offset=".901" class="m8gjscclp"/></radialGradient><radialGradient id="i3G4iLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.41287 -1.9196 0 16.005 17.153)" gradientUnits="userSpaceOnUse"><stop class="dwgp50w0z"/><stop offset="1" class="qe-mijbxt"/></radialGradient><radialGradient id="idEKDPc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.948 20.87)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i688l3c" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 10.028 12.278)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ilFILib" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.893 10.847)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i63Hz6d" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.602 8.154)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="idOG2kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.532 9.534)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iW4MHRY" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.7 -2.127)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="io5eboc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.518 11.835)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iWyakRb" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.293 8.114)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iJJpysa" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.205 13.81)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iuVYUbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53125 -5.6944 0 16.132 7.77)" gradientUnits="userSpaceOnUse"><stop offset=".432" class="oaje9ccjt"/><stop offset="1" class="c1-5xjjaj"/></radialGradient><radialGradient id="i5C141b" cx="0" cy="0" r="1" gradientTransform="scale(9.97024 6.8088)rotate(90 .06 1.559)" gradientUnits="userSpaceOnUse"><stop offset=".581" class="q-hyakboh"/><stop offset=".963" class="kh43xnjra"/><stop offset="1" class="dr22motxg"/></radialGradient><radialGradient id="iuQsE1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.551 12.207)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="itL8p1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.667 11.637)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iBFGewe" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.986 8.982)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="idDuSfV" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.594 14.47)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iAI8Hfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.267 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8yAhde" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.039 10.014)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iklbSXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.903 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZ9ggrt" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.617 10.15)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i31PT2d" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.703 9.944)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iSaHKHb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.063 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i9jEGGc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.177 10.661)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i8mj8Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.17 10.585)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iA2Dtpv" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.17 10.588)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="iqUNw9c" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iDW3OSc" x1="18.442" x2="17.099" y1="16.497" y2="18.247" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iAnzatc" x1="10.357" x2="11.077" y1="7.888" y2="7.888" gradientUnits="userSpaceOnUse"><stop class="y6ren_9gl"/><stop offset="1" class="mivtz_dos"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="irJlSKb" x1="21.242" x2="18.713" y1="12.532" y2="12.532" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i8Z4hdV" x1="16.923" x2="16.085" y1="11.521" y2="11.556" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iC1HOnb" x1="16.085" x2="16.085" y1="12.66" y2="12.195" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="i3A2C3d" x1="16.085" x2="16.085" y1="9.955" y2="10.704" gradientUnits="userSpaceOnUse"><stop class="g4tdpvbfe"/><stop offset="1" class="cakruex-k"/></linearGradient><linearGradient id="iDT3ANJ" x1="16.501" x2="16.501" y1="12.798" y2="12.605" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="ioyTlhe" x1="14.883" x2="15.202" y1="14.231" y2="13.397" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="infS0Pe" x1="19.045" x2="18.731" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5uvc5u" x1="14.647" x2="14.333" y1="9.984" y2="10.177" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAACKkc" x1="22.521" x2="21.314" y1="10.011" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i8FgrNb" x1="10.235" x2="11.694" y1="10.715" y2="10.588" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iLYSsTc" x1="21.501" x2="21.501" y1="9.629" y2="11.533" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iJIPMLc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYqfV7X" x1="18.083" x2="16.597" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient><filter id="inat2Ic" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".5"/></filter><filter id="ipOtYzc" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".5"/></filter><filter id="iqilsge" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2461" result="effect2_innerShadow_4002_2461"/></filter><filter id="ibnH8Rb" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".5"/></filter><filter id="iGBye1b" width="3.042" height="14.123" x="18.465" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2461" result="effect2_innerShadow_4002_2461"/></filter><filter id="ixne0QG" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2461" result="effect2_innerShadow_4002_2461"/></filter><filter id="iodpwIV" width="3.989" height="1.699" x="13.935" y="16.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.184314 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/></filter><filter id="iAA1Jyz" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".1"/></filter><filter id="iLtfkXb" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2461" result="effect2_innerShadow_4002_2461"/></filter><filter id="iaSthnT" width="11.22" height="12.542" x="11.022" y="4.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2461" result="effect2_innerShadow_4002_2461"/></filter><filter id="ifpSSsZ" width="3.747" height="4.9" x="14.07" y="9.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".5"/></filter><filter id="iALUqPO" width="2.277" height="3.3" x="14.946" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".1"/></filter><filter id="iUeNVfY" width="3.718" height="1.573" x="14.226" y="13.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".05"/></filter><filter id="iGzbWkd" width=".787" height=".696" x="17.533" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".05"/></filter><filter id="igEcqlB" width=".891" height=".913" x="18.373" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".1"/></filter><filter id="ieUBGQd" width=".986" height="1.04" x="13.93" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".1"/></filter><filter id="iVHMcdc" width=".913" height=".704" x="13.175" y="9.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".05"/></filter><filter id="ih5YONe" width="1.329" height="2.379" x="10.004" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".125"/></filter><filter id="iEpdB2c" width="1.947" height="2.903" x="20.528" y="9.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".25"/></filter><filter id="iB1aPhb" width="10.9" height="2.77" x="10.555" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/></filter><filter id="idNmDme" width="4.831" height="2.64" x="13.59" y="2.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2461" stdDeviation=".125"/></filter><filter id="ivXemTc" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/></filter><filter id="i79LSxR" width="2.298" height="1.22" x="15.943" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/></filter><filter id="iViYK0d" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2461"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pilot-medium-dark" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a4fn021uw {
  d: path("M18.27 9.453a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.c-ym95agn {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.703 10.132l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.c1-5xjjaj {
  stop-color: var(--svg-color--623647, #623647);
  stop-opacity: 0;
}

.cakruex-k {
  stop-color: var(--svg-color--754b4f, #754B4F);
  stop-opacity: 0;
}

.call61qec {
  d: path("M13.9 9.453a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.cvz-zbs5l {
  d: path("M11.224 12.096a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d-rslkbmf {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.793 4.351h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.006l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d8vxffbru {
  d: path("M13.295 15.837q-.691.176-1.345.435l-.035.019l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dr22motxg {
  stop-color: var(--svg-color--7b3773, #7B3773);
}

.ds7rl_bqv {
  d: path("M20.946 12.096c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.dsfnryq2l {
  stop-color: var(--svg-color--c0aac0, #C0AAC0);
}

.dwgp50w0z {
  stop-color: var(--svg-color--703557, #703557);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3skdu--u {
  stop-color: var(--svg-color--928392, #928392);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e8en5ebgp {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.694 9.181c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etg525soo {
  d: path("M11.26 13.611a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
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

.fy172u3yk {
  d: path("m15.703 10.132l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.765 0");
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g0nms2b_d {
  stop-color: var(--svg-color--373133, #373133);
}

.g4tdpvbfe {
  stop-color: var(--svg-color--754b4f, #754B4F);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.glm72l-sq {
  fill: var(--svg-color--000, #000);
  d: path("M17.758 10.346a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hoi6qtbym {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.476 9.182c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.127");
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j4yxb8m0i {
  d: path("M16.085 13.743c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.334.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.j7qzs0bmp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.204 9.642c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
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

.k5tflqgkr {
  d: path("M21.007 12.187q.101-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kflbiccup {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.13.096.25.22.25h.152c.18 0 .18.079.213.149c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.219l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.kh43xnjra {
  stop-color: var(--svg-color--783d61, #783D61);
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.l00gxpbma {
  d: path("M10.357 6.319h.719v3.752h-.719z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lx4tcbb_k {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.684 10.328l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.505-.408-.615 0");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m8gjscclp {
  stop-color: var(--svg-color--231b20, #231B20);
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mivtz_dos {
  stop-color: var(--svg-color--271e21, #271E21);
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n7k0g1b5l {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.645l-.22-10.445l.09-.183q.507.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nczmykb2q {
  d: path("M23.13 18.123V30h3.865v-3.5c0-3.356-1.5-6.36-3.865-8.377");
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o9j-zubkj {
  d: path("M14.716 10.24c0-.288-.234-.48-.298-.538l-.288.279l.177.361z");
}

.oaje9ccjt {
  stop-color: var(--svg-color--623647, #623647);
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

.oq2p_zbtm {
  d: path("M18.204 9.642c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.ouoob-ulp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.27c-.54.784-1.546 2.2-1.85 2.874c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
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

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q-hyakboh {
  stop-color: var(--svg-color--784559, #784559);
  stop-opacity: 0;
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qckr5_bvx {
  d: path("M16.005 18.445c1.789-.788 1.932-1.316 1.919-1.7h-3.838c-.013.384.224.97 1.919 1.7");
}

.qe-mijbxt {
  stop-color: var(--svg-color--73415b, #73415B);
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

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.s7h2pnz4x {
  d: path("M21.028 11.533q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.sd_er748d {
  d: path("M19.064 10.228a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sv13rb7yi {
  stop-color: var(--svg-color--68565a, #68565A);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t69swbctq {
  fill: var(--svg-color--000, #000);
  d: path("M14.412 10.346a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.thyaubczg {
  d: path("M11.04 8.983a1.62 1.62 0 0 0-1.391 1.598c0 .86.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.ttv23cfgz {
  cx: 13.632px;
  cy: 9.834px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.utoue4ayv {
  d: path("M21.131 6.319h.719v3.752h-.719z");
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v6z_k_d_d {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.141z");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vvnobeb4d {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.05l.117-.182q.653.173 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w5aybu7rs {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.734 13.348a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wa_uxbcpj {
  d: path("M11 9.648a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.084-1.88");
}

.wb9snib6m {
  d: path("M21.747 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y6ren_9gl {
  stop-color: var(--svg-color--463d3b, #463D3B);
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

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zklpcnmjw {
  cx: 13.632px;
  cy: 9.834px;
  rx: 0.39px;
  ry: 0.197px;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
