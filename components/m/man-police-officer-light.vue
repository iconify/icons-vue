<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#iYsmUsd)"><path class="w4srnfb7y"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#ip75Wos)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="htxp2lohr"/><path fill="url(#iaSWI7d)" class="htxp2lohr"/><path fill="url(#ihSlXYc)" class="htxp2lohr"/><g filter="url(#itThMKR)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#ijoToEe)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#ix6vz4b)" class="jdcv0xbln"/><g filter="url(#iAqQB9v)"><path fill="url(#ii91opc)" class="vnlonib2h"/><path fill="url(#in3v7nb)" class="vnlonib2h"/></g><g filter="url(#iibwVFe)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#iG1gqBd)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><g filter="url(#idFHQId)"><circle fill="url(#iXswgId)" class="xxjch-b_k"/></g><g filter="url(#itSoIHp)"><circle fill="url(#ius5RGc)" class="h7vf7qb4p"/></g><g filter="url(#iK9bSVb)"><circle fill="url(#iAz77sb)" class="jfcedi9nu"/><circle fill="url(#iyNfDbe)" class="jfcedi9nu"/></g><g filter="url(#ip0CEeR)"><circle class="azj97zk0r"/><circle fill="url(#iP3xazc)" class="c-2o1_bto"/><circle fill="url(#i4EL7Sb)" class="c-2o1_bto"/></g><g filter="url(#iX6XYXd)"><path fill="url(#id0Vs9w)" class="du82yvb1g"/></g><path fill="url(#igTpzvc)" class="du82yvb1g"/><path fill="url(#i6KymVc)" class="du82yvb1g"/><path fill="url(#irXgkMc)" class="du82yvb1g"/><path fill="url(#iIgXCoe)" class="du82yvb1g"/><path fill="url(#iAuyEWf)" class="du82yvb1g"/><path fill="url(#irFkaWd)" class="du82yvb1g"/><path fill="url(#iks87xb)" class="du82yvb1g"/><path fill="url(#iatu5Lz)" class="du82yvb1g"/><g filter="url(#iZNM1Sc)"><path class="xnmu9lb0k"/><path fill="url(#iDqnQsb)" class="n-b_v-bio"/><path fill="url(#ifIEZvb)" class="n-b_v-bio"/><path fill="url(#i31roXc)" class="n-b_v-bio"/><path fill="url(#iKQfvQd)" class="n-b_v-bio"/></g><g filter="url(#ikkdtJV)"><path class="txp2nqbng"/></g><g filter="url(#itanKFc)"><path class="jv65cobwh"/><path fill="url(#iIAHruJ)" class="v2rwikphs"/><path fill="url(#iNfN0Vg)" class="v2rwikphs"/><path fill="url(#iNEYWtc)" class="v2rwikphs"/><path fill="url(#iXBZmII)" class="v2rwikphs"/></g><g filter="url(#iXw6X4b)"><path fill="url(#i6JbwQc)" class="omngs09es"/></g><g filter="url(#iKk9U3d)"><path stroke="url(#iwrvOfd)" class="fgqsrlbof"/></g><path class="qvacwtsvu"/><path class="oadwx9b9n"/><path fill="url(#itWHFOf)" class="pg6zsbbfg"/><path class="cwqytxbup"/><g filter="url(#iBFOuGb)"><path class="t-96ucblh"/><path fill="url(#iGdwGPd)" class="mwz4gnt6x"/></g><g filter="url(#i4q6ZJW)"><path fill="url(#ifXMVLq)" class="g_a-ivoau"/></g><path class="x_u0pcbof"/><path fill="url(#iXsCWJe)" class="el6xqnbxd"/><path class="df-om_piv"/><g filter="url(#iQCcm6d)"><path fill="url(#i3AJDlb)" class="zhnmo_bny"/></g><g filter="url(#izncILe)"><ellipse transform="rotate(-27.914 12.998 11.958)" class="vc8cq-b8s"/><ellipse fill="url(#idWkzbd)" transform="rotate(-27.914 12.998 11.958)" class="mh3x8ibjg"/></g><g filter="url(#il9sCDb)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#ixhD7Bb)"><path class="trw5-7ral"/></g><g filter="url(#iHRitqe)"><path fill="url(#iBrxMjb)" class="nta8ypj0m"/></g><g filter="url(#i8dcSnd)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#iwBDixs)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#iLGmxib)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="qfni0kjsa"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="qfni0kjsa"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="qfni0kjsa"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="ix6vz4b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="ii91opc" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="yy69dgnjz"/><stop offset="1" class="qxh-jcb9e"/></radialGradient><radialGradient id="in3v7nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="i39qv0blz"/><stop offset="1" class="xxn25rbwf"/></radialGradient><radialGradient id="iXswgId" cx="0" cy="0" r="1" gradientTransform="matrix(2.01663 0 0 3.52912 8.445 12.852)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iyNfDbe" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 30.136 -27.095)scale(1.17519 1.34133)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iP3xazc" cx="0" cy="0" r="1" gradientTransform="matrix(.94376 -1.73585 1.016 .5524 21.248 13.795)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="i4EL7Sb" cx="0" cy="0" r="1" gradientTransform="matrix(.29797 .29493 -.38022 .38413 21.295 12.851)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="id0Vs9w" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09775 0 0 -10.3573 19.073 13.3)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i6KymVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.9824 -12.0593 0 16.364 6.726)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="doxrpybdd"/><stop offset=".988" class="g_9wdfbqx"/></radialGradient><radialGradient id="irXgkMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28609 1.65755 0 18.652 11.83)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iIgXCoe" cx="0" cy="0" r="1" gradientTransform="rotate(-89.786 12.52 -.641)scale(1.22554 1.38899)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iAuyEWf" cx="0" cy="0" r="1" gradientTransform="rotate(176.531 9.683 7.503)scale(9.92788 24.3584)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="irFkaWd" cx="0" cy="0" r="1" gradientTransform="matrix(3.61398 -3.67092 1.34578 1.3249 9.42 8.455)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iks87xb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03325 3.22874 -2.71461 -1.70948 18.629 7.723)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iatu5Lz" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.87179 -7.50905 0 15.253 10.645)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="b4lzsmbqd"/><stop offset="1" class="x3l3c-xdj"/></radialGradient><radialGradient id="iDqnQsb" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.716 -9.52)scale(3.51917 1.30502)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ifIEZvb" cx="0" cy="0" r="1" gradientTransform="matrix(4.39537 .40448 -.21749 2.36336 18.925 6.11)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i31roXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92965 -2.98848 0 15.82 2.968)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iKQfvQd" cx="0" cy="0" r="1" gradientTransform="matrix(3.53247 -2.58869 4.05562 5.53422 8.409 10.803)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iXBZmII" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22627 -.72695 0 16.195 14.698)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="itWHFOf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93212 -1.48265 0 18.323 12.068)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGdwGPd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.01 1.66)scale(.43461 .59837)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXsCWJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93217 -1.48272 0 13.31 12.068)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idWkzbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00889 -.56765 .68234 -.01068 12.98 12.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iYsmUsd" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".25"/></filter><filter id="ip75Wos" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="itThMKR" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="ijoToEe" width="3.6" height="4.539" x="15.879" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="iAqQB9v" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.45098 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="iibwVFe" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2691" result="effect2_innerShadow_4002_2691"/></filter><filter id="iG1gqBd" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2691" result="effect2_innerShadow_4002_2691"/></filter><filter id="idFHQId" width="4.037" height="3.837" x="8.445" y="10.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="itSoIHp" width="3.287" height="3.287" x="8.72" y="11.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".25"/></filter><filter id="iK9bSVb" width="4.087" height="4.087" x="19.377" y="10.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="ip0CEeR" width="3.287" height="3.287" x="19.652" y="11.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".25"/></filter><filter id="iX6XYXd" width="12.921" height="14.022" x="9.892" y="6.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2691" result="effect2_innerShadow_4002_2691"/></filter><filter id="iZNM1Sc" width="14.481" height="9.743" x="8.579" y="2.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="ikkdtJV" width="3.522" height="4.581" x="13.784" y="11.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".375"/></filter><filter id="itanKFc" width="2.657" height="3.581" x="14.491" y="11.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".125"/></filter><filter id="iXw6X4b" width="2.657" height="3.581" x="14.491" y="11.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".125"/></filter><filter id="iKk9U3d" width="4.098" height="1.633" x="13.771" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".05"/></filter><filter id="iBFOuGb" width=".874" height=".77" x="17.495" y="11.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".05"/></filter><filter id="i4q6ZJW" width=".964" height=".99" x="18.475" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".1"/></filter><filter id="iQCcm6d" width="1.074" height="1.136" x="13.37" y="11.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".1"/></filter><filter id="izncILe" width="1.019" height=".78" x="12.488" y="11.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".05"/></filter><filter id="il9sCDb" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><filter id="ixhD7Bb" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".075"/></filter><filter id="iHRitqe" width="2.624" height="2.748" x="14.643" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2691" result="effect2_innerShadow_4002_2691"/></filter><filter id="i8dcSnd" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2691" result="effect2_innerShadow_4002_2691"/></filter><filter id="iwBDixs" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2691" stdDeviation=".25"/></filter><filter id="iLGmxib" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2691"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="ius5RGc" x1="10.363" x2="9.627" y1="13.172" y2="13.172" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iAz77sb" x1="22.544" x2="21.603" y1="11.598" y2="14.512" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="igTpzvc" x1="21.813" x2="16.736" y1="15.187" y2="15.187" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iIAHruJ" x1="14.826" x2="15.905" y1="14.057" y2="14.057" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iNfN0Vg" x1="16.898" x2="15.719" y1="14.428" y2="14.411" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iNEYWtc" x1="16.043" x2="16.043" y1="15.281" y2="14.622" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="i6JbwQc" x1="15.819" x2="16.122" y1="12.067" y2="13.876" gradientUnits="userSpaceOnUse"><stop class="p12q4lqjb"/><stop offset="1" class="dt-pzp1tk"/></linearGradient><linearGradient id="iwrvOfd" x1="14.628" x2="15.128" y1="17.137" y2="16.347" gradientUnits="userSpaceOnUse"><stop class="qru1b9dcl"/><stop offset=".663" class="j7knnob6o"/></linearGradient><linearGradient id="ifXMVLq" x1="19.217" x2="18.857" y1="12.13" y2="12.352" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3AJDlb" x1="14.164" x2="13.804" y1="12.13" y2="12.352" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iBrxMjb" x1="16.899" x2="14.793" y1="4.542" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer-light" /></template>
<style>
.a2jurmb2n {
  stop-color: var(--svg-color--3183ce, #3183CE);
}

.a565onb9e {
  stop-color: var(--svg-color--33488b, #33488B);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a8t42xt1y {
  stop-color: var(--svg-color--36a5fc, #36A5FC);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.azj97zk0r {
  cx: 21.296px;
  cy: 12.852px;
  r: 1.143px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.b4lzsmbqd {
  stop-color: var(--svg-color--b37c7b, #B37C7B);
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c-2o1_bto {
  cx: 21.296px;
  cy: 12.852px;
  r: 1.143px;
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cwqytxbup {
  fill: var(--svg-color--000, #000);
  d: path("M17.738 12.546c0-.327.261-.588.588-.588a.585.585 0 0 1 .522.858h-1.04a.53.53 0 0 1-.07-.27");
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.df-om_piv {
  fill: var(--svg-color--000, #000);
  d: path("M13.895 12.546a.585.585 0 0 0-.588-.588a.585.585 0 0 0-.522.858h1.04a.6.6 0 0 0 .07-.27");
}

.doxrpybdd {
  stop-color: var(--svg-color--cd96a0, #CD96A0);
  stop-opacity: 0;
}

.dt-pzp1tk {
  stop-color: var(--svg-color--ca968f, #CA968F);
  stop-opacity: 0;
}

.du82yvb1g {
  d: path("M9.892 10.495c0-.307.123-.674.37-.858l.185-.184c.308-.245.431-.613.431-.98v-.981c0-.307.185-.552.493-.613c.74-.184 2.281-.49 4.5-.49c2.22 0 3.76.306 4.5.49c.246.061.493.306.493.613v.98c0 .368.185.736.431.98c.577.405.541.628.494 1.104c-.062.613-.124 1.655-.124 1.655h.021l-.305 4.549c-.185 2.033-1.783 3.45-3.69 3.45h-3.689c-1.968 0-3.505-1.417-3.69-3.45c-.16-2.088-.23-4.181-.42-6.265");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.el6xqnbxd {
  d: path("M13.307 11.52a1.025 1.025 0 0 0-.988 1.296H14.3q.036-.134.037-.27a1.03 1.03 0 0 0-1.03-1.026");
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.ewagz7_9h {
  stop-color: var(--svg-color--3a84b9, #3A84B9);
}

.f1vhuirkb {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
  stop-opacity: 0;
}

.f5rlg0klg {
  width: 4.156px;
  height: 1.234px;
  x: 8.939px;
  y: 25.977px;
  rx: 0.15px;
}

.f69-7cs4d {
  stop-color: var(--svg-color--55d2ff, #55D2FF);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fgqsrlbof {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.82 16.449a3.45 3.45 0 0 1-1.592-.378c-.158-.08-.327.098-.228.24a2.17 2.17 0 0 0 1.82.973c.763 0 1.434-.39 1.819-.973c.099-.148-.07-.32-.228-.24c-.46.24-1.003.378-1.592.378Z");
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g_9wdfbqx {
  stop-color: var(--svg-color--b888a5, #B888A5);
}

.g_a-ivoau {
  d: path("M19.24 12.41a.97.97 0 0 0-.267-.531l-.298.327l.134.263z");
}

.g-3ft7k9f {
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g3qn2hbkl {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.727a1.406 1.406 0 0 1-2.813 0z");
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h7vf7qb4p {
  cx: 10.363px;
  cy: 12.852px;
  r: 1.143px;
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.htxp2lohr {
  d: path("m17.577 29.934l-.927-5.202a.15.15 0 0 0-.147-.123h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i39qv0blz {
  stop-color: var(--svg-color--b7899d, #B7899D);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.j2ao_sb9l {
  d: path("M8.797 4.266c-.625.258-1.356 1.025-.969 2.375s.526 1.802.547 1.86c.04.166.223.5.633.5h.39a.46.46 0 0 0 .301-.134c.142-.134 2.254-1.596 5.827-1.718c3.645.122 6.633 1.584 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.116-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.j7knnob6o {
  stop-color: var(--svg-color--e9b3a7, #E9B3A7);
  stop-opacity: 0;
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.jfcedi9nu {
  cx: 21.296px;
  cy: 12.852px;
  r: 1.918px;
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jv65cobwh {
  fill: var(--svg-color--e2af9c, #E2AF9C);
  d: path("m15.38 12.524l-.61 1.953a.62.62 0 0 0 .598.804h.903a.622.622 0 0 0 .598-.804l-.61-1.953c-.131-.433-.742-.433-.879 0");
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mh3x8ibjg {
  cx: 12.998px;
  cy: 11.958px;
  rx: 0.448px;
  ry: 0.227px;
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mwz4gnt6x {
  d: path("M18.25 11.737c.073.098-.08.217-.253.347c-.174.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.n-b_v-bio {
  d: path("m21.357 5.408l.493.245c.863.429 1.356 1.41 1.171 2.452l-.678 3.493c-.06.36-.299.604-.657.613h-.02s.061-1.042.123-1.655c.05-.498-.037-.65-.494-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.219 0-3.76.306-4.5.49a.6.6 0 0 0-.493.613v.98c0 .368-.123.736-.431.98l-.185.185c-.247.184-.37.551-.37.858c.062.674.123 1.655.123 1.655l-.056-.002a.73.73 0 0 1-.683-.611l-.679-3.494c-.123-.98.37-1.961 1.233-2.39l.493-.245c.309-.184.617-.43.925-.674l1.11-1.165c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.973-.06 2.713.613l.925.92c.246.306.554.49.924.674");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.nta8ypj0m {
  d: path("M14.793 3.757v.922a1.187 1.187 0 0 0 2.374 0v-.924a.2.2 0 0 0-.308-.168l-.252.16a.1.1 0 0 1-.134-.025l-.295-.402a.25.25 0 0 0-.403 0l-.292.401a.1.1 0 0 1-.135.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.oadwx9b9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.563 11.208c.75 0 1.385.517 1.557 1.216a.315.315 0 0 1-.308.392H17.25a.264.264 0 0 1-.26-.313a1.606 1.606 0 0 1 1.574-1.295");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.omngs09es {
  d: path("m15.38 12.392l-.61 1.953a.62.62 0 0 0 .598.803h.903a.622.622 0 0 0 .598-.803l-.61-1.953c-.131-.433-.742-.433-.879 0");
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.p12q4lqjb {
  stop-color: var(--svg-color--ca968f, #CA968F);
}

.pg6zsbbfg {
  d: path("M18.326 11.52a1.025 1.025 0 0 1 .988 1.296h-1.98a1.03 1.03 0 0 1 .993-1.296");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qfni0kjsa {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.854-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.432c2.085-.862 7.432-2.032 12.945-.012a.775.775 0 1 1-.533 1.455");
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qru1b9dcl {
  stop-color: var(--svg-color--e9b3a7, #E9B3A7);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qvacwtsvu {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.82 16.449a3.45 3.45 0 0 1-1.592-.378c-.158-.08-.327.098-.228.24a2.17 2.17 0 0 0 1.82.973c.763 0 1.434-.39 1.819-.973c.099-.148-.07-.32-.228-.24c-.46.24-1.003.378-1.592.378");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxh-jcb9e {
  stop-color: var(--svg-color--b98e9a, #B98E9A);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.t-96ucblh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.25 11.737c.073.098-.08.217-.253.347c-.174.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.t9xlhbbtl {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
}

.thtcysb5g {
  d: path("M8.055 29.934H3.862a12.15 12.15 0 0 1 4.193-8.309z");
}

.tp8jvfpml {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
  stop-opacity: 0;
}

.trkjkfbvt {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.trw5-7ral {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.169l-.253.161a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.025l-.247-.158a.2.2 0 0 0-.308.169");
}

.ts35s1bpk {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.769-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.txp2nqbng {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.503 12.712l-.943 1.953c-.117.401.164.803.561.803h.847c.398 0 .678-.408.561-.803l-.572-1.953c-.123-.433-.325-.433-.454 0");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v2rwikphs {
  d: path("m15.38 12.524l-.61 1.953a.62.62 0 0 0 .598.804h.903a.622.622 0 0 0 .598-.804l-.61-1.953c-.131-.433-.742-.433-.879 0");
}

.vc8cq-b8s {
  cx: 12.998px;
  cy: 11.958px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vnlonib2h {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.652 2.145-2.223l-2.145-.332z");
}

.w4srnfb7y {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.079.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x_u0pcbof {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.07 11.208c-.75 0-1.385.517-1.557 1.216c-.052.2.102.392.307.392h2.564c.163 0 .293-.15.26-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.x3l3c-xdj {
  stop-color: var(--svg-color--b37c7b, #B37C7B);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xnmu9lb0k {
  fill: var(--svg-color--242324, #242324);
  d: path("m21.357 5.408l.493.245c.863.429 1.356 1.41 1.171 2.452l-.678 3.493c-.06.36-.299.604-.657.613h-.02s.061-1.042.123-1.655c.05-.498-.037-.65-.494-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.219 0-3.76.306-4.5.49a.6.6 0 0 0-.493.613v.98c0 .368-.123.736-.431.98l-.185.185c-.247.184-.37.551-.37.858c.062.674.123 1.655.123 1.655l-.056-.002a.73.73 0 0 1-.683-.611l-.679-3.494c-.123-.98.37-1.961 1.233-2.39l.493-.245c.309-.184.617-.43.925-.674l1.11-1.165c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.973-.06 2.713.613l.925.92c.246.306.554.49.924.674");
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xxjch-b_k {
  cx: 10.363px;
  cy: 12.852px;
  r: 1.918px;
}

.xxn25rbwf {
  stop-color: var(--svg-color--b7899d, #B7899D);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.yy69dgnjz {
  stop-color: var(--svg-color--c09aa7, #C09AA7);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhnmo_bny {
  d: path("M14.244 12.425c0-.331-.27-.552-.342-.62l-.332.321l.204.415z");
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
