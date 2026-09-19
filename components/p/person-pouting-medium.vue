<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ie0DIOb)" class="odq2frbdh"/><path fill="url(#iik7kQo)" class="odq2frbdh"/><path fill="url(#iO2aVKU)" class="odq2frbdh"/><rect fill="url(#igwAF4c)" class="o9uu_2vuf"/><rect fill="url(#i8E9Gvc)" class="o9uu_2vuf"/><path fill="url(#iFHmW8d)" class="lpley2bsg"/><path fill="url(#ifbmyGd)" class="pz8_28qcs"/><path fill="url(#iNp5okb)" class="pz8_28qcs"/><g filter="url(#iVsvTFk)"><path fill="url(#i8yxIQb)" class="ixbfuabjj"/></g><path fill="url(#iayzFSO)" class="ixbfuabjj"/><path fill="url(#iEkJHmc)" class="ixbfuabjj"/><path fill="url(#iOX2Cvc)" class="ixbfuabjj"/><path fill="url(#id5sDLb)" class="ixbfuabjj"/><g filter="url(#iDFFX5d)"><path fill="url(#iBFRQid)" class="h2xwtmsbp"/></g><path fill="url(#iSnF9Bb)" class="h2xwtmsbp"/><path fill="url(#iCT0rAP)" class="c3yjfvnsc"/><path fill="url(#iSWObHc)" class="dcgirob1g"/><g filter="url(#i1Wb0Ie)"><path fill="url(#iXrnJsc)" class="ylz24ebth"/><path fill="url(#ibmUhkc)" class="ylz24ebth"/></g><path fill="url(#iNaM1xD)" class="ylz24ebth"/><path fill="url(#iTOipAe)" class="ylz24ebth"/><path fill="url(#iea2cNe)" class="ylz24ebth"/><path fill="url(#ikLjiNY)" class="ylz24ebth"/><path fill="url(#izuu7be)" class="ylz24ebth"/><path fill="url(#iUKUNpc)" class="ylz24ebth"/><path fill="url(#idKrtcd)" class="ylz24ebth"/><path fill="url(#i2l6Koc)" class="ylz24ebth"/><g filter="url(#ibJJzwc)"><path fill="url(#iNSW7Be)" class="jv6f4q9lg"/><path fill="url(#ia4ZGpd)" class="jv6f4q9lg"/></g><g filter="url(#iLq4Rke)"><path class="qoz8641gl"/></g><g filter="url(#i546bkT)"><path class="adf3z-csk"/><path fill="url(#iJqgBVu)" class="np8wn1bye"/><path fill="url(#ixOd0Xc)" class="np8wn1bye"/><path fill="url(#i3luPpe)" class="np8wn1bye"/><path fill="url(#iO5woxd)" class="np8wn1bye"/><path fill="url(#iZCp08p)" class="np8wn1bye"/></g><path fill="url(#i2DLykh)" class="np8wn1bye"/><path fill="url(#i5Yb1he)" class="np8wn1bye"/><g filter="url(#izpJOdd)"><path fill="url(#iYQTZTc)" class="c9g6n7bcr"/><path fill="url(#iR3L6Yb)" class="c9g6n7bcr"/><path fill="url(#ieOqETd)" class="c9g6n7bcr"/><path fill="url(#i7uY1VP)" class="c9g6n7bcr"/><path fill="url(#iEXtkve)" class="c9g6n7bcr"/></g><g filter="url(#iMAgcDc)"><path class="svxx9nbeh"/><path fill="url(#iWQGXBF)" class="e18amabvc"/><path fill="url(#iKMjgNd)" class="e18amabvc"/></g><g filter="url(#iYFBoMb)"><path class="bfx9yebib"/><path fill="url(#igNwKVc)" class="b5fw5qw-x"/><path fill="url(#ikBQOVD)" class="b5fw5qw-x"/><path fill="url(#ivyepud)" class="b5fw5qw-x"/></g><path class="a_duvgb9e"/><path fill="url(#ixGPBuz)" class="b_aqr-bzt"/><path class="ul6r6qqcl"/><g filter="url(#ikUQLSi)"><path class="loy193btd"/><path fill="url(#iHGDn1H)" class="ifntehb7a"/></g><g filter="url(#iL5jHyc)"><path fill="url(#iQ8Pz0c)" class="hprp_wr_e"/></g><path class="q8-oeye6j"/><path fill="url(#iXSEaFc)" class="f2q_pvnpf"/><path class="a6l7cobbk"/><g filter="url(#iGKbkZb)"><path fill="url(#ibmc0md)" class="f-kdkxbir"/></g><g filter="url(#iXXMQGW)"><ellipse transform="rotate(-27.914 13.549 9.823)" class="f34fq48cl"/><ellipse fill="url(#i8xnFHR)" transform="rotate(-27.914 13.549 9.823)" class="m8cxozbfz"/></g><path fill="url(#iIfhcIe)" class="fdsit0bjg"/><path fill="url(#ilhtodb)" class="fdsit0bjg"/><path fill="url(#iyPFMnc)" class="fdsit0bjg"/><path fill="url(#idGzd2c)" class="fdsit0bjg"/><path fill="url(#iRzGrhc)" class="o4p5dcbip"/><path fill="url(#iftTAjt)" class="o4p5dcbip"/><g filter="url(#iFvfw8b)"><path fill="url(#ivJsxrx)" class="m0vpygb0n"/></g><g filter="url(#iUfLTbd)"><path fill="url(#iwGVKoe)" class="jfspu_b3c"/></g><path class="cr5vr7bum"/><path stroke="url(#i1PRUre)" class="pib2qys9v"/><path stroke="url(#inQiNnc)" class="pib2qys9v"/><g filter="url(#iUVIgke)"><rect class="uy1fgdbyq"/></g><g filter="url(#ih6VWde)"><rect class="b40-ntb-t"/></g><g filter="url(#iLn7V2b)"><path stroke="url(#iEcfWOe)" class="sapyqx2rl"/></g><g filter="url(#isTkwDb)"><path stroke="url(#ioxyGjd)" class="pvvgkqb9d"/></g><defs><radialGradient id="ie0DIOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02197 9.09668 -14.16842 3.14929 14.022 14.59)" gradientUnits="userSpaceOnUse"><stop class="khj8zwb0j"/><stop offset=".674" class="dt2jwkbti"/></radialGradient><radialGradient id="iik7kQo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.71875 9.5625 0 21.73 24.313)" gradientUnits="userSpaceOnUse"><stop class="osixu2bon"/><stop offset="1" class="bh4gs6bci"/></radialGradient><radialGradient id="igwAF4c" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -8.964 24.325)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="j6xccjbtl"/><stop offset="1" class="q3_ltc6vo"/></radialGradient><radialGradient id="i8E9Gvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.918 16.625)" gradientUnits="userSpaceOnUse"><stop class="q9z2_uxsx"/><stop offset="1" class="o8q-rhbvy"/></radialGradient><radialGradient id="iNp5okb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -9.0144 10.168 23.313)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="pyz9maawt"/><stop offset="1" class="j5lcx07ey"/></radialGradient><radialGradient id="i8yxIQb" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.71 24.842)" gradientUnits="userSpaceOnUse"><stop class="fgr-87b3i"/><stop offset="1" class="fose66bdc"/></radialGradient><radialGradient id="iEkJHmc" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.536 26.617)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="ltebjbiko"/><stop offset="1" class="h42giz8mi"/></radialGradient><radialGradient id="iOX2Cvc" cx="0" cy="0" r="1" gradientTransform="rotate(166.054 12.159 14.007)scale(5.39674 1.22772)" gradientUnits="userSpaceOnUse"><stop class="c2k9t5bpp"/><stop offset="1" class="x1r12ebov"/></radialGradient><radialGradient id="id5sDLb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.255 12.758 9.535)scale(3.73328 6.83692)" gradientUnits="userSpaceOnUse"><stop class="sl_nofb5a"/><stop offset=".499" class="u-i19nmvm"/></radialGradient><radialGradient id="iBFRQid" cx="0" cy="0" r="1" gradientTransform="matrix(.71233 3.34406 -18.37025 3.9131 16.143 24.53)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="brkowxetu"/><stop offset="1" class="dwpx8zbde"/></radialGradient><radialGradient id="iCT0rAP" cx="0" cy="0" r="1" gradientTransform="matrix(.74816 2.01788 -2.39708 .88876 20.75 11.775)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iSWObHc" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.99 38.55)scale(1.5464 4.77073)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iXrnJsc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70118 0 0 -8.31633 18.805 10.834)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ibmUhkc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.56 8.125)scale(3.36622 2.77909)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iTOipAe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02144 12.41335 -10.27976 -.84587 17.581 4.926)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iea2cNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14741 1.41992 0 18.445 9.522)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="ikLjiNY" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09338 1.18985 .00428 13.701 9.568)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="izuu7be" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.529 6.217)scale(8.50592 21.7283)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iUKUNpc" cx="0" cy="0" r="1" gradientTransform="matrix(3.383 -2.91408 .86077 .99928 9.214 8.103)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="idKrtcd" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.165 13.765)scale(2.50638 1.00191)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i2l6Koc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87087 -1.67183 0 13.786 10.34)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ixOd0Xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2439 -.76655 0 16.466 12.194)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iO5woxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69067 .74948 -1.20448 -2.71705 16.582 11.625)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="i5Yb1he" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28118 1.22257 -1.76448 -1.84907 16.432 11.336)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iR3L6Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.49845 8.84718 0 10.775 7.944)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="p2s973_gj"/><stop offset="1" class="p6dlq8bal"/></radialGradient><radialGradient id="ieOqETd" cx="0" cy="0" r="1" gradientTransform="matrix(.11396 -2.51048 4.44808 .2019 20.857 9.253)" gradientUnits="userSpaceOnUse"><stop class="gpki0lbqt"/><stop offset="1" class="jxp-9c9su"/></radialGradient><radialGradient id="i7uY1VP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74785 -1.59807 1.17306 -2.01706 19.127 2.841)" gradientUnits="userSpaceOnUse"><stop class="g6v8l_bkd"/><stop offset="1" class="gs7m3x8bv"/></radialGradient><radialGradient id="iEXtkve" cx="0" cy="0" r="1" gradientTransform="matrix(.90437 1.47379 -3.4126 2.0941 15.095 1.391)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="ptziuobjj"/><stop offset="1" class="irfbnmbhq"/></radialGradient><radialGradient id="iWQGXBF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19932 0 0 -.81625 16.253 3.649)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iKMjgNd" cx="0" cy="0" r="1" gradientTransform="matrix(3.21553 -5.09127 5.6406 3.56248 10.574 7.588)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="igNwKVc" cx="0" cy="0" r="1" gradientTransform="matrix(3.05588 0 0 1.1948 19.411 4.425)" gradientUnits="userSpaceOnUse"><stop class="wkq1lrbro"/><stop offset="1" class="ay2ml8bfu"/></radialGradient><radialGradient id="ikBQOVD" cx="0" cy="0" r="1" gradientTransform="matrix(2.95643 -2.64605 4.84424 5.41247 18.631 7.46)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ivyepud" cx="0" cy="0" r="1" gradientTransform="matrix(3.22262 .72355 -.30294 1.34925 17.769 5.64)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="ixGPBuz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81065 -1.28944 0 18.18 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iHGDn1H" cx="0" cy="0" r="1" gradientTransform="matrix(-.23173 -.29861 .41112 -.31903 17.952 10.003)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXSEaFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8107 -1.2895 0 13.82 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8xnFHR" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49368 .59342 -.0093 13.534 10.138)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilhtodb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.758 18.558)scale(2.32776 2.22086)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iyPFMnc" cx="0" cy="0" r="1" gradientTransform="matrix(.78713 -1.08022 .90544 .65978 20.974 10.477)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="idGzd2c" cx="0" cy="0" r="1" gradientTransform="matrix(.58652 -1.54915 2.06988 .78367 21.088 10.649)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iftTAjt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65689 0 0 -1.85016 11.088 10.573)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="ivJsxrx" cx="0" cy="0" r="1" gradientTransform="matrix(-.91573 .15719 -.16117 -.9389 11.09 10.576)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i1PRUre" cx="0" cy="0" r="1" gradientTransform="matrix(.1551 -.37929 .9046 .36994 16.756 14.13)" gradientUnits="userSpaceOnUse"><stop class="xfrt5eolg"/><stop offset="1" class="w6gxpjb6l"/></radialGradient><radialGradient id="inQiNnc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.305 23.527 -9.823)scale(.32552 .2228)" gradientUnits="userSpaceOnUse"><stop class="xfrt5eolg"/><stop offset="1" class="w6gxpjb6l"/></radialGradient><linearGradient id="iO2aVKU" x1="17.426" x2="17.426" y1="30.357" y2="26.753" gradientUnits="userSpaceOnUse"><stop class="s9luuo8wr"/><stop offset="1" class="mw-dyzb9n"/></linearGradient><linearGradient id="iFHmW8d" x1="22.967" x2="24.881" y1="22.469" y2="22.469" gradientUnits="userSpaceOnUse"><stop offset=".17" class="h-4-uqb4q"/><stop offset="1" class="k-xmaur5i"/></linearGradient><linearGradient id="ifbmyGd" x1="8.98" x2="6.915" y1="23.313" y2="22.849" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ev32s2_gl"/><stop offset="1" class="p1zhkctql"/></linearGradient><linearGradient id="iayzFSO" x1="16.051" x2="16.387" y1="29.707" y2="25.82" gradientUnits="userSpaceOnUse"><stop class="xf1vn5u9l"/><stop offset="1" class="eppadln1r"/></linearGradient><linearGradient id="iSnF9Bb" x1="15.688" x2="15.094" y1="28.25" y2="26.063" gradientUnits="userSpaceOnUse"><stop class="dceu0b-1x"/><stop offset="1" class="eyli-ebiy"/></linearGradient><linearGradient id="iNaM1xD" x1="21.153" x2="18.626" y1="12.518" y2="12.518" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iNSW7Be" x1="15.488" x2="16.284" y1="14.436" y2="14.239" gradientUnits="userSpaceOnUse"><stop class="aa2nlnqvl"/><stop offset=".522" class="my6a1rx3x"/></linearGradient><linearGradient id="ia4ZGpd" x1="16.047" x2="16.047" y1="14.822" y2="14.47" gradientUnits="userSpaceOnUse"><stop offset=".207" class="y3s8qdl-c"/><stop offset="1" class="q192v5b4y"/></linearGradient><linearGradient id="iJqgBVu" x1="16.837" x2="16" y1="11.508" y2="11.543" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i3luPpe" x1="16" x2="16" y1="12.647" y2="12.182" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iZCp08p" x1="16" x2="16" y1="9.944" y2="10.49" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="i2DLykh" x1="16.415" x2="16.415" y1="12.784" y2="12.592" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iYQTZTc" x1="22.846" x2="11.244" y1="5.176" y2="5.176" gradientUnits="userSpaceOnUse"><stop class="ej5y0weeq"/><stop offset="1" class="fj0i7pb1f"/></linearGradient><linearGradient id="iQ8Pz0c" x1="18.957" x2="18.644" y1="9.973" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibmc0md" x1="14.563" x2="14.249" y1="9.973" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIfhcIe" x1="22.431" x2="21.225" y1="10" y2="12.174" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iRzGrhc" x1="10.155" x2="11.612" y1="10.703" y2="10.576" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iwGVKoe" x1="21.448" x2="21.448" y1="9.691" y2="11.447" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iEcfWOe" x1="19.435" x2="16.618" y1="8.711" y2="8.711" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bl_6lzkvy"/><stop offset="1" class="g9zuepbcp"/></linearGradient><linearGradient id="ioxyGjd" x1="14.929" x2="12.111" y1="8.711" y2="8.711" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bl_6lzkvy"/><stop offset="1" class="g9zuepbcp"/></linearGradient><filter id="iVsvTFk" width="19.161" height="7.244" x="8.205" y="22.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.352941 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/></filter><filter id="iDFFX5d" width="19.009" height="7.177" x="5.218" y="22.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.392157 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/></filter><filter id="i1Wb0Ie" width="11.212" height="12.532" x="10.941" y="4.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4638" result="effect2_innerShadow_13036_4638"/></filter><filter id="ibJJzwc" width="1.224" height=".712" x="15.388" y="14.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".05"/></filter><filter id="iLq4Rke" width="3.745" height="4.898" x="13.985" y="9.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".5"/></filter><filter id="i546bkT" width="2.276" height="3.298" x="14.862" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".1"/></filter><filter id="izpJOdd" width="12.862" height="8.35" x="9.569" y="1.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4638" result="effect2_innerShadow_13036_4638"/></filter><filter id="iMAgcDc" width="7.079" height="6.487" x="9.674" y="2.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/><feGaussianBlur result="effect2_foregroundBlur_13036_4638" stdDeviation=".25"/></filter><filter id="iYFBoMb" width="7.356" height="6.231" x="15.591" y="2.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.152941 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/><feGaussianBlur result="effect2_foregroundBlur_13036_4638" stdDeviation=".25"/></filter><filter id="ikUQLSi" width=".786" height=".696" x="17.447" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".05"/></filter><filter id="iL5jHyc" width=".891" height=".913" x="18.286" y="9.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".1"/></filter><filter id="iGKbkZb" width=".986" height="1.04" x="13.847" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".1"/></filter><filter id="iXXMQGW" width=".912" height=".704" x="13.092" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".05"/></filter><filter id="iFvfw8b" width="1.328" height="2.378" x="9.924" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".125"/></filter><filter id="iUfLTbd" width="1.805" height="2.756" x="20.546" y="9.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".25"/></filter><filter id="iUVIgke" width="2.748" height=".641" x="12.416" y="8.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.133333 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/></filter><filter id="ih6VWde" width="2.748" height=".641" x="16.935" y="8.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.133333 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4638"/></filter><filter id="iLn7V2b" width="2.77" height=".7" x="16.945" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".125"/></filter><filter id="isTkwDb" width="2.77" height=".7" x="12.438" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4638" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-pouting-medium" /></template>
<style>
.a_duvgb9e {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.389 9.17c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.226-.272a1.4 1.4 0 0 1 1.37-1.126");
}

.a6l7cobbk {
  fill: var(--svg-color--000, #000);
  d: path("M14.328 10.334a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .06-.235");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aa2nlnqvl {
  stop-color: var(--svg-color--aa8378, #AA8378);
}

.adf3z-csk {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.618 10.12l-.531 1.837c-.109.378.152.756.52.756h.786c.368 0 .628-.384.52-.756l-.531-1.837c-.114-.407-.645-.407-.764 0");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ay2ml8bfu {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
  stop-opacity: 0;
}

.b_aqr-bzt {
  d: path("M18.182 9.442a.892.892 0 0 1 .86 1.127h-1.723a.895.895 0 0 1 .863-1.127");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b40-ntb-t {
  width: 2.648px;
  height: 0.541px;
  x: 16.935px;
  y: 8.487px;
  fill: var(--svg-color--482d2c, #482D2C);
  rx: 0.271px;
}

.b5fw5qw-x {
  d: path("m21.208 8.487l-.029-.63c-.01-.763-.641-1.393-1.404-1.425h-1.4a2.42 2.42 0 0 1-2.121-1.258s-.059-.135-.12-.367c-.257-.97.67-1.712 1.656-1.521c.972.189 2.079.516 2.898 1.05c1.743 1.137 1.438 3.186.52 4.151");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfx9yebib {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.208 8.487l-.029-.63c-.01-.763-.641-1.393-1.404-1.425h-1.4a2.42 2.42 0 0 1-2.121-1.258s-.059-.135-.12-.367c-.257-.97.67-1.712 1.656-1.521c.972.189 2.079.516 2.898 1.05c1.743 1.137 1.438 3.186.52 4.151");
}

.bh4gs6bci {
  stop-color: var(--svg-color--ff6646, #FF6646);
  stop-opacity: 0;
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl_6lzkvy {
  stop-color: var(--svg-color--5a4344, #5A4344);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.brkowxetu {
  stop-color: var(--svg-color--c89b88, #C89B88);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c2k9t5bpp {
  stop-color: var(--svg-color--c9a083, #C9A083);
}

.c3yjfvnsc {
  d: path("M20.857 12.083c.335-.01.649-.124.904-.308v.93a2.17 2.17 0 0 1-1.34 2.017q.256-.544.346-1.179z");
}

.c9g6n7bcr {
  d: path("M20.85 4.197a2.32 2.32 0 0 1 1.267 1.05c.467.82.398 1.8-.106 2.524c-.174.258-.27.563-.27.874v1.187a1.7 1.7 0 0 0-.667-.268l.079-1.605a1.45 1.45 0 0 0-1.378-1.43h-1.399a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.615-.418H14.28c-1.845 0-3.34 1.512-3.34 3.377l.032 1.536a1.7 1.7 0 0 0-.72.263V8.645c0-.31-.096-.616-.27-.874a2.39 2.39 0 0 1-.143-2.443a2.34 2.34 0 0 1 1.298-1.126a2.68 2.68 0 0 0 1.383-1.11a2.32 2.32 0 0 1 2.888-.91c.382.166.811.166 1.193 0a2.4 2.4 0 0 1 .911-.188c.843 0 1.58.456 1.987 1.131c.308.51.79.879 1.352 1.072");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr5vr7bum {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M15.148 14.13c.488-.335 1.211-.336 1.705 0a.28.28 0 0 0 .314-.46c-.682-.466-1.656-.466-2.335 0a.28.28 0 1 0 .316.46");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dceu0b-1x {
  stop-color: var(--svg-color--ac7380, #AC7380);
}

.dcgirob1g {
  d: path("M11.143 12.083a1.64 1.64 0 0 1-.904-.308v.93a2.17 2.17 0 0 0 1.34 2.017a4 4 0 0 1-.346-1.179z");
}

.dt2jwkbti {
  stop-color: var(--svg-color--fc4a2b, #FC4A2B);
}

.dwpx8zbde {
  stop-color: var(--svg-color--ad886e, #AD886E);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e18amabvc {
  d: path("m16.232 5.223l-.066-.137a.66.66 0 0 0-.615-.418H14.28c-1.845 0-3.34 1.512-3.34 3.377v.275c-.339-.259-.766-.804-.766-1.687c0-1.07.78-1.612 1.28-1.957c.14-.098.258-.18.33-.253l.1-.105c.348-.37.97-1.03 2.057-1.319a5.5 5.5 0 0 1 1.506-.165c.473.011.806.42.806.893V5.21z");
}

.ej5y0weeq {
  stop-color: var(--svg-color--6f514d, #6F514D);
}

.eppadln1r {
  stop-color: var(--svg-color--995b74, #995B74);
  stop-opacity: 0;
}

.ev32s2_gl {
  stop-color: var(--svg-color--ff5437, #FF5437);
}

.eyli-ebiy {
  stop-color: var(--svg-color--ac7380, #AC7380);
  stop-opacity: 0;
}

.f-kdkxbir {
  d: path("M14.633 10.23c0-.29-.235-.481-.298-.54l-.288.28l.177.36z");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f2q_pvnpf {
  d: path("M13.818 9.442a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.896-.892");
}

.f34fq48cl {
  cx: 13.549px;
  cy: 9.823px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fdsit0bjg {
  d: path("M20.918 12.174q.1-1.594.184-3.189a1.608 1.608 0 0 1-.184 3.189");
}

.fgr-87b3i {
  stop-color: var(--svg-color--b58b7f, #B58B7F);
}

.fj0i7pb1f {
  stop-color: var(--svg-color--523d3b, #523D3B);
}

.fose66bdc {
  stop-color: var(--svg-color--b88669, #B88669);
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g6v8l_bkd {
  stop-color: var(--svg-color--563937, #563937);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.g9zuepbcp {
  stop-color: var(--svg-color--5a4344, #5A4344);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gpki0lbqt {
  stop-color: var(--svg-color--473033, #473033);
}

.gs7m3x8bv {
  stop-color: var(--svg-color--563937, #563937);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.h-4-uqb4q {
  stop-color: var(--svg-color--ff491d, #FF491D);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h2xwtmsbp {
  d: path("M5.668 28.531c-.6-1.05-.453-2.812-.375-3.597l3.937-.168c.413.212 1.527.088 2.032 0l9.672-1.563c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.064.077c-4.285 1.54-12.404 4.814-13.524 5.063c-1.82.312-3.695-.04-4.445-1.352");
}

.h42giz8mi {
  stop-color: var(--svg-color--875269, #875269);
  stop-opacity: 0;
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hprp_wr_e {
  d: path("M18.976 10.216a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.ifntehb7a {
  d: path("M18.117 9.63c.063.086-.07.19-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.135.389-.05");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.irfbnmbhq {
  stop-color: var(--svg-color--654f4c, #654F4C);
  stop-opacity: 0;
}

.ixbfuabjj {
  d: path("M26.417 28.531c.6-1.05.453-2.812.375-3.597l-3.938-.168c-.412.212-1.526.088-2.03 0l-8.898-1.407c-.617-.117-2.097-.231-2.774.133c-.765.412-1 1.193-.937 1.578c4.27 1.532 12.632 4.563 13.757 4.813c1.82.312 3.695-.04 4.445-1.352");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j5lcx07ey {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
}

.j6xccjbtl {
  stop-color: var(--svg-color--763c3c, #763C3C);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jfspu_b3c {
  d: path("M21.046 11.447q.05-.877.094-1.756c.4.054.711.425.711.874c0 .485-.36.878-.805.882");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jv6f4q9lg {
  d: path("M16.512 14.692a.512.512 0 0 0-1.024 0z");
}

.jxp-9c9su {
  stop-color: var(--svg-color--473033, #473033);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k-xmaur5i {
  stop-color: var(--svg-color--ff6747, #FF6747);
}

.khj8zwb0j {
  stop-color: var(--svg-color--a72503, #A72503);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.loy193btd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.117 9.63c.063.086-.07.19-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.135.389-.05");
}

.lpley2bsg {
  d: path("M22.967 17.937a10.48 10.48 0 0 1 3.827 7.019l-3.827-.18z");
}

.ltebjbiko {
  stop-color: var(--svg-color--875269, #875269);
}

.m0vpygb0n {
  d: path("M10.919 9.637a.955.955 0 0 0 .083 1.878a78 78 0 0 1-.083-1.878");
}

.m8cxozbfz {
  cx: 13.549px;
  cy: 9.823px;
  rx: 0.389px;
  ry: 0.197px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw-dyzb9n {
  stop-color: var(--svg-color--d73726, #D73726);
  stop-opacity: 0;
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.my6a1rx3x {
  stop-color: var(--svg-color--905f54, #905F54);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.np8wn1bye {
  d: path("m15.618 10.12l-.531 1.837c-.109.378.152.756.52.756h.786c.368 0 .628-.384.52-.756l-.531-1.837c-.114-.407-.645-.407-.764 0");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o4p5dcbip {
  d: path("M10.96 8.972c-.78.11-1.391.786-1.391 1.597c0 .858.672 1.56 1.52 1.605a78 78 0 0 1-.13-3.202");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.o8q-rhbvy {
  stop-color: var(--svg-color--64332a, #64332A);
  stop-opacity: 0;
}

.o9uu_2vuf {
  width: 4.223px;
  height: 6.028px;
  x: 13.918px;
  y: 12.688px;
  rx: 2.111px;
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odq2frbdh {
  d: path("m9.2 24.75l-3.906.183c.577-5.253 5.03-9.34 10.436-9.34h.625c5.415 0 9.872 4.099 10.44 9.363l-4.378-.206v5.188H9.2z");
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.osixu2bon {
  stop-color: var(--svg-color--ff6547, #FF6547);
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.p1zhkctql {
  stop-color: var(--svg-color--ff3a19, #FF3A19);
}

.p2s973_gj {
  stop-color: var(--svg-color--53403e, #53403E);
}

.p6dlq8bal {
  stop-color: var(--svg-color--53403e, #53403E);
  stop-opacity: 0;
}

.pib2qys9v {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.148 14.13c.488-.335 1.211-.336 1.705 0a.28.28 0 0 0 .314-.46c-.682-.466-1.656-.466-2.335 0a.28.28 0 1 0 .316.46");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.ptziuobjj {
  stop-color: var(--svg-color--654f4c, #654F4C);
}

.pvvgkqb9d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.788 8.71h2.07");
}

.pyz9maawt {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
  stop-opacity: 0;
}

.pz8_28qcs {
  d: path("m5.294 24.934l3.847-.16l.058.182h.031v-7.109a10.5 10.5 0 0 0-3.936 7.086");
}

.q192v5b4y {
  stop-color: var(--svg-color--a27370, #A27370);
  stop-opacity: 0;
}

.q3_ltc6vo {
  stop-color: var(--svg-color--8f5549, #8F5549);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q8-oeye6j {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.611 9.17c-.653 0-1.204.45-1.354 1.058c-.044.175.09.34.268.34h2.23a.23.23 0 0 0 .226-.27a1.4 1.4 0 0 0-1.37-1.128");
}

.q9z2_uxsx {
  stop-color: var(--svg-color--64332a, #64332A);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qoz8641gl {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.599 10.316l-.59 1.837c-.101.377.14.755.483.755h.732c.342 0 .584-.383.484-.755l-.494-1.837c-.106-.407-.504-.407-.615 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s9luuo8wr {
  stop-color: var(--svg-color--d73726, #D73726);
}

.sapyqx2rl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.295 8.71h2.07");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sl_nofb5a {
  stop-color: var(--svg-color--997b66, #997B66);
}

.svxx9nbeh {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.232 5.223l-.066-.137a.66.66 0 0 0-.615-.418H14.28c-1.845 0-3.34 1.512-3.34 3.377v.275c-.339-.259-.766-.804-.766-1.687c0-1.07.78-1.612 1.28-1.957c.14-.098.258-.18.33-.253l.1-.105c.348-.37.97-1.03 2.057-1.319a5.5 5.5 0 0 1 1.506-.165c.473.011.806.42.806.893V5.21z");
}

.u-i19nmvm {
  stop-color: var(--svg-color--997b66, #997B66);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ul6r6qqcl {
  fill: var(--svg-color--000, #000);
  d: path("M17.671 10.334c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.06-.235");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uy1fgdbyq {
  width: 2.648px;
  height: 0.541px;
  x: 12.416px;
  y: 8.487px;
  fill: var(--svg-color--2f1e1d, #2F1E1D);
  rx: 0.271px;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w6gxpjb6l {
  stop-color: var(--svg-color--bc9386, #BC9386);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wkq1lrbro {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
}

.x1r12ebov {
  stop-color: var(--svg-color--c9a083, #C9A083);
  stop-opacity: 0;
}

.xf1vn5u9l {
  stop-color: var(--svg-color--995b74, #995B74);
}

.xfrt5eolg {
  stop-color: var(--svg-color--bc9386, #BC9386);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.y3s8qdl-c {
  stop-color: var(--svg-color--a27370, #A27370);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.ylz24ebth {
  d: path("M11.179 13.597A3.91 3.91 0 0 0 15.062 17h1.885a3.91 3.91 0 0 0 3.882-3.403c.118-1.882.236-3.757.324-5.638a1.45 1.45 0 0 0-1.378-1.43h-1.399a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.615-.418H14.28c-1.845 0-3.34 1.512-3.34 3.377c0 1.859.117 3.688.239 5.552");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
