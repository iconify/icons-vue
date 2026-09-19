<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#imzeprd)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="b072x2aii"/><path fill="url(#iqdGPbc)" class="b072x2aii"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#imxr95F)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#iz4nIUc)"><path class="yqf7_qb9p"/></g><path fill="url(#ii5h9Zd)" class="q9zrzf44o"/><g filter="url(#iZTAred)"><path class="ujx_tn9cg"/></g><g filter="url(#iuS2ixe)"><path fill="url(#iMm4Ddd)" class="u0ana6wkh"/><path fill="url(#ideVytc)" class="u0ana6wkh"/><path fill="url(#iNjTTxJ)" class="u0ana6wkh"/></g><path fill="url(#iXFEZTd)" class="u0ana6wkh"/><g filter="url(#itE24re)"><path class="liskm4bco"/></g><g filter="url(#iZwdnlb)"><path fill="url(#itFU7Nd)" class="fc6zhkb0f"/><path fill="url(#ipIpBme)" class="fc6zhkb0f"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#i56uO1c)" class="gael-ox4b"/><path fill="url(#iacojZb)" class="gt17cd57p"/><g filter="url(#ibEqvWI)"><circle fill="url(#iii24Gd)" class="glbnwvb_a"/></g><g filter="url(#izIW9ie)"><circle fill="url(#ifJi2YH)" class="y8ur0olbc"/></g><g filter="url(#iFlu2CT)"><circle fill="url(#iznIWCd)" class="sdtw-ebka"/><circle fill="url(#i8kaHye)" class="sdtw-ebka"/></g><g filter="url(#iyDKTqz)"><circle class="hy209abbl"/><circle fill="url(#i6vWDZK)" class="a0yke01vl"/><circle fill="url(#iNbFNCe)" class="a0yke01vl"/></g><g filter="url(#iBqgTue)"><path fill="url(#i6S5VYS)" class="vp8_u44pn"/><path fill="url(#iXzQ1Wc)" class="vp8_u44pn"/><path fill="url(#iUVV1Zo)" class="vp8_u44pn"/><path fill="url(#itX2Yge)" class="vp8_u44pn"/><path fill="url(#ix3PHfc)" class="vp8_u44pn"/><path fill="url(#iXPpWYb)" class="vp8_u44pn"/></g><g filter="url(#ihby1Pd)"><path class="f0jj_8_ps"/></g><g filter="url(#igP3p4b)"><path class="r5bvnjb-j"/><path fill="url(#iyqk2rb)" class="yo0qq74eb"/><path fill="url(#i8vhfzA)" class="yo0qq74eb"/><path fill="url(#iLh430b)" class="yo0qq74eb"/><path fill="url(#ifR3rfd)" class="yo0qq74eb"/><path fill="url(#iIvJeEb)" class="yo0qq74eb"/></g><path stroke="url(#iBkWg6d)" class="z0ml5j7uz"/><path class="lie3m6bhb"/><path fill="url(#i2rpA2d)" class="xchvhxb7x"/><path class="y88xgfx7j"/><g filter="url(#ixn0zYd)"><path class="tu69vgb1t"/><path fill="url(#ikILXXl)" class="e985s9iub"/></g><g filter="url(#iFi4sCm)"><path fill="url(#i99Q9jb)" class="kfq23acby"/></g><path class="gkd52r1-n"/><path fill="url(#iY7OWTd)" class="bkyeejbgi"/><path class="t3_xevb-o"/><g filter="url(#iEV1cGd)"><path fill="url(#ihJM2Md)" class="iq8bm6byr"/></g><g filter="url(#iTrAG6a)"><ellipse transform="rotate(-27.914 13.518 9.775)" class="p_1zpgbzu"/><ellipse fill="url(#iaq2aPb)" transform="rotate(-27.914 13.518 9.775)" class="pz3_9xbne"/></g><g filter="url(#i4UchxA)"><path class="twmd3hfji"/><path fill="url(#iB5EloS)" class="hcavqkbyc"/><path fill="url(#ijDnjme)" class="hcavqkbyc"/><path fill="url(#iaHK1KG)" class="hcavqkbyc"/><path fill="url(#iC326Hb)" class="hcavqkbyc"/></g><g filter="url(#ijEZHvd)"><path fill="url(#iMNODVc)" class="ftk3zsbyc"/></g><g filter="url(#ikS2Dud)"><path class="r9pg4ucoe"/></g><g filter="url(#iRVS0Pd)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#icitDsz)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iJIPMLc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#i7TdDlm)"><path class="ho8k-2bnl"/></g><g filter="url(#i5mMSBd)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#iudIiib)"><path fill="url(#iR42Amc)" class="hdde0uvpo"/></g><g filter="url(#inzTpWb)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="imzeprd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.404)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="ii5h9Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.99 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iacojZb" cx="0" cy="0" r="1" gradientTransform="scale(1.9196 2.0625)rotate(90 .01 8.327)" gradientUnits="userSpaceOnUse"><stop class="a0lhb1bwk"/><stop offset="1" class="nlmx7rbrv"/></radialGradient><radialGradient id="iii24Gd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.552 10.553)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="i8kaHye" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.118 10.288)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i6vWDZK" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.704 11.375)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iNbFNCe" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.746 10.553)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iUVV1Zo" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.13088 -8.29998 0 15.674 9.832)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="h-g0ieb0u"/><stop offset=".947" class="ihoxe7big"/><stop offset="1" class="wieetqpaw"/></radialGradient><radialGradient id="itX2Yge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.324 9.28)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="ix3PHfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.762 9.247)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iXPpWYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.80585 -4.88736 0 15.995 8.137)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="ps4smfbok"/><stop offset="1" class="oru-2_bhd"/></radialGradient><radialGradient id="ifR3rfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.303 12.161)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i2rpA2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.157 9.87)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ikILXXl" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.929 9.955)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iY7OWTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.79 9.87)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iaq2aPb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.718 -1.602)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iB5EloS" cx="0" cy="0" r="1" gradientTransform="matrix(.79855 -2.7904 1.08822 .31143 20.334 6.645)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ijDnjme" cx="0" cy="0" r="1" gradientTransform="matrix(3.82846 .33219 -.16857 1.94277 18.69 4.985)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iaHK1KG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.58476 -2.60303 0 15.985 2.403)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iC326Hb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.126 3.2672 4.72843 9.53 8.838)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="imxr95F" x1="9.135" x2="6.942" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="i56uO1c" x1="18.818" x2="17.747" y1="18.66" y2="18.66" gradientUnits="userSpaceOnUse"><stop class="k3yv484oe"/><stop offset="1" class="gi8--rb6p"/></linearGradient><linearGradient id="ifJi2YH" x1="11.223" x2="10.582" y1="10.832" y2="10.832" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iznIWCd" x1="21.833" x2="21.014" y1="9.461" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i6S5VYS" x1="20.016" x2="12.372" y1="10.943" y2="12.082" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iXzQ1Wc" x1="10.575" x2="12.842" y1="13.642" y2="13.5" gradientUnits="userSpaceOnUse"><stop offset=".283" class="wy-63vfsm"/><stop offset="1" class="v7nb2nb5g"/></linearGradient><linearGradient id="iyqk2rb" x1="15.111" x2="16.05" y1="11.603" y2="11.603" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i8vhfzA" x1="16.915" x2="15.889" y1="11.926" y2="11.911" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iLh430b" x1="16.171" x2="16.171" y1="12.669" y2="12.095" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iIvJeEb" x1="15.976" x2="15.976" y1="9.985" y2="10.798" gradientUnits="userSpaceOnUse"><stop class="of3m4rv_h"/><stop offset="1" class="qyd9bsbrt"/></linearGradient><linearGradient id="iBkWg6d" x1="14.938" x2="15.373" y1="14.285" y2="13.597" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i99Q9jb" x1="18.935" x2="18.621" y1="9.924" y2="10.118" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihJM2Md" x1="14.534" x2="14.22" y1="9.924" y2="10.118" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iJIPMLc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iR42Amc" x1="18.083" x2="16.597" y1="3.169" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient><filter id="iz4nIUc" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".5"/></filter><filter id="iZTAred" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".5"/></filter><filter id="iuS2ixe" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2460" result="effect2_innerShadow_4002_2460"/></filter><filter id="itE24re" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".5"/></filter><filter id="iZwdnlb" width="3.042" height="14.123" x="18.465" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2460" result="effect2_innerShadow_4002_2460"/></filter><filter id="ibEqvWI" width="3.542" height="3.342" x="9.552" y="8.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="izIW9ie" width="2.992" height="2.992" x="9.728" y="9.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".25"/></filter><filter id="iFlu2CT" width="3.592" height="3.592" x="19.075" y="8.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="iyDKTqz" width="2.992" height="2.992" x="19.25" y="9.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".25"/></filter><filter id="iBqgTue" width="10.402" height="12.139" x="10.794" y="4.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="ihby1Pd" width="3.262" height="4.184" x="14.106" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".375"/></filter><filter id="igP3p4b" width="2.379" height="3.184" x="14.787" y="9.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".125"/></filter><filter id="ixn0zYd" width=".787" height=".697" x="17.422" y="9.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".05"/></filter><filter id="iFi4sCm" width=".892" height=".914" x="18.263" y="9.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".1"/></filter><filter id="iEV1cGd" width=".987" height="1.041" x="13.817" y="9.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".1"/></filter><filter id="iTrAG6a" width=".914" height=".705" x="13.061" y="9.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".05"/></filter><filter id="i4UchxA" width="12.614" height="8.1" x="9.678" y="1.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="ijEZHvd" width="2.735" height="2.58" x="14.632" y="18.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2460" result="effect2_innerShadow_4002_2460"/></filter><filter id="ikS2Dud" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".1"/></filter><filter id="iRVS0Pd" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2460" result="effect2_innerShadow_4002_2460"/></filter><filter id="icitDsz" width="10.9" height="2.77" x="10.555" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="i7TdDlm" width="4.831" height="2.64" x="13.59" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2460" stdDeviation=".125"/></filter><filter id="i5mMSBd" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="iudIiib" width="2.298" height="1.22" x="15.944" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter><filter id="inzTpWb" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2460"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-pilot-dark" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a0lhb1bwk {
  stop-color: var(--svg-color--35162b, #35162B);
}

.a0yke01vl {
  cx: 20.746px;
  cy: 10.553px;
  r: 0.996px;
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b072x2aii {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.378");
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bkyeejbgi {
  d: path("M13.788 9.393a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
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

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e985s9iub {
  d: path("M18.093 9.582c.064.085-.07.189-.22.302c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.f0jj_8_ps {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.7 10.43l-.82 1.702c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fc6zhkb0f {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.05l.117-.182q.653.173 1.272.423l1.26 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftk3zsbyc {
  d: path("m14.732 19.661l1.267-1.098l1.268 1.075l-.546 1.265a.24.24 0 0 1-.217.14h-1.021a.24.24 0 0 1-.216-.14z");
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

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi8--rb6p {
  stop-color: var(--svg-color--9c92a5, #9C92A5);
  stop-opacity: 0;
}

.gkd52r1-n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.58 9.121c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.232a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.373-1.13");
}

.glbnwvb_a {
  cx: 11.223px;
  cy: 10.553px;
  r: 1.671px;
}

.gt17cd57p {
  d: path("M16.005 18.445c1.789-.788 1.932-1.316 1.919-1.7h-3.838c-.013.384.224.971 1.919 1.7");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h-g0ieb0u {
  stop-color: var(--svg-color--3f1c39, #3F1C39);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hcavqkbyc {
  d: path("m20.808 4.407l.43.202a1.826 1.826 0 0 1 1.02 2.013l-.59 2.87a.6.6 0 0 1-.596.512c.035-.476.077-1.25.09-1.372c.043-.408-.01-.53-.408-.902c-.214-.202-.375-.504-.375-.806V6.12c0-.252-.215-.453-.43-.503c-.644-.151-1.986-.403-3.92-.403c-1.932 0-3.274.252-3.919.403a.5.5 0 0 0-.43.503v.805c0 .302-.107.604-.375.806l-.161.15c-.215.152-.323.467-.323.719c.014.147.035.992.059 1.344c-.3-.02-.544-.215-.595-.502l-.59-2.87a1.9 1.9 0 0 1 1.073-1.962c1.015-.42 1.384-1.056 2.201-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0a2.52 2.52 0 0 1 2.362.504l.806.755c.215.251.483.402.805.553");
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
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

.hy209abbl {
  cx: 20.746px;
  cy: 10.553px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.ihoxe7big {
  stop-color: var(--svg-color--3f1c39, #3F1C39);
}

.iq8bm6byr {
  d: path("M14.604 10.181c0-.288-.235-.48-.298-.539l-.29.28l.178.36z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k3yv484oe {
  stop-color: var(--svg-color--665c72, #665C72);
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kfq23acby {
  d: path("M18.954 10.169a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lie3m6bhb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.366 9.121c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34H17.22a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.liskm4bco {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.508.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nlmx7rbrv {
  stop-color: var(--svg-color--3c1b32, #3C1B32);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.of3m4rv_h {
  stop-color: var(--svg-color--3d262a, #3D262A);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.oru-2_bhd {
  stop-color: var(--svg-color--2f1b26, #2F1B26);
  stop-opacity: 0;
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p_1zpgbzu {
  cx: 13.518px;
  cy: 9.775px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.p81iumb5r {
  stop-color: var(--svg-color--6d6675, #6D6675);
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

.ps4smfbok {
  stop-color: var(--svg-color--2f1b26, #2F1B26);
}

.pz3_9xbne {
  cx: 13.518px;
  cy: 9.775px;
  rx: 0.39px;
  ry: 0.197px;
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
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

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyd9bsbrt {
  stop-color: var(--svg-color--3d262a, #3D262A);
  stop-opacity: 0;
}

.r5bvnjb-j {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.593 10.268l-.532 1.701a.54.54 0 0 0 .521.7h.787c.37 0 .63-.356.521-.7l-.532-1.701c-.114-.377-.645-.377-.765 0");
}

.r9pg4ucoe {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.612c-.22 0-.42.13-.515.329c-.01.02-.039.02-.039 0a.57.57 0 0 0-.515-.33h-.592c-.125 0-.23.09-.24.22s.096.25.22.25h.153c.18 0 .18.079.213.15a.34.34 0 0 0 .306.198h.238l.54.13c.133 0 .46-.1.518-.22l.086-.199a.1.1 0 0 1 .095-.06h.144c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
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

.sdtw-ebka {
  cx: 20.746px;
  cy: 10.553px;
  r: 1.671px;
}

.t3_xevb-o {
  fill: var(--svg-color--000, #000);
  d: path("M14.3 10.286a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.tu69vgb1t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.093 9.582c.064.085-.07.189-.22.302c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.twmd3hfji {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.808 4.407l.43.202a1.826 1.826 0 0 1 1.02 2.013l-.59 2.87a.6.6 0 0 1-.596.512c.035-.476.077-1.25.09-1.372c.043-.408-.01-.53-.408-.902c-.214-.202-.375-.504-.375-.806V6.12c0-.252-.215-.453-.43-.503c-.644-.151-1.986-.403-3.92-.403c-1.932 0-3.274.252-3.919.403a.5.5 0 0 0-.43.503v.805c0 .302-.107.604-.375.806l-.161.15c-.215.152-.323.467-.323.719c.014.147.035.992.059 1.344c-.3-.02-.544-.215-.595-.502l-.59-2.87a1.9 1.9 0 0 1 1.073-1.962c1.015-.42 1.384-1.056 2.201-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0a2.52 2.52 0 0 1 2.362.504l.806.755c.215.251.483.402.805.553");
}

.u0ana6wkh {
  d: path("M13.295 15.837q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ujx_tn9cg {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.271c-.54.783-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.894 6.334z");
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.v7nb2nb5g {
  stop-color: var(--svg-color--5d4d49, #5D4D49);
  stop-opacity: 0;
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vp8_u44pn {
  d: path("M10.794 8.496c0-.267.126-.583.341-.743l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.161.641.376.855c.502.352.471.545.43.96a47 47 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006c-.14-1.826-.28-3.692-.386-5.461");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
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

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wieetqpaw {
  stop-color: var(--svg-color--401943, #401943);
}

.wy-63vfsm {
  stop-color: var(--svg-color--5d4d49, #5D4D49);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xchvhxb7x {
  d: path("M18.159 9.393a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y88xgfx7j {
  fill: var(--svg-color--000, #000);
  d: path("M17.647 10.286a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.y8ur0olbc {
  cx: 11.223px;
  cy: 10.553px;
  r: 0.996px;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.yo0qq74eb {
  d: path("m15.593 10.268l-.532 1.701a.54.54 0 0 0 .521.7h.787c.37 0 .63-.356.521-.7l-.532-1.701c-.114-.377-.645-.377-.765 0");
}

.yqf7_qb9p {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348h-2.516v4.74c0 .31.335.49.567.29l1.949-1.67l1.95 1.67c.231.2.566.02.566-.29v-4.74z");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z0ml5j7uz {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.613 13.313c.393.205.863.323 1.363.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .021.241m-2.99-.281l2.948.253m-2.947-.253a.2.2 0 0 0-.243.042a.19.19 0 0 0-.02.24m.263-.282l-.222.253m3.211.028l-.042-.027m.042.027l-.042-.027m.042.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.846-1.584.846s-1.25-.338-1.585-.847m-.041.028v.001l.041-.029m-.041.028l.041-.027");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

</style>
