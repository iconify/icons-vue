<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iw7DLYb)"><path fill="url(#ieTn7Mb)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iOQ8Zae)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#ixa2hWc)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iLL68lb)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iG2mDDe)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#imIaxEb)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iH6ryxQ)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#i3B1LBb)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#ivNHvJt)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iITlE0g)" clip-rule="evenodd" class="n6lo_jd-m"/><path fill="url(#iH3BIgM)" clip-rule="evenodd" class="n6lo_jd-m"/></g><g filter="url(#iytFOte)"><path fill="url(#i1gsgse)" class="ix50_xb6d"/><path fill="url(#i8XiPOe)" class="ix50_xb6d"/><path fill="url(#iJls1sc)" class="ix50_xb6d"/><path fill="url(#iKpeIKe)" class="ix50_xb6d"/><path fill="url(#iW1L1sc)" class="ix50_xb6d"/><path fill="url(#iUkKPae)" class="ix50_xb6d"/><path fill="url(#is3wVfe)" class="ix50_xb6d"/><path fill="url(#isUixxc)" class="ix50_xb6d"/></g><g filter="url(#iKlkkGe)"><path fill="url(#iMgi8Bd)" class="ohgemac2l"/></g><g filter="url(#iM74y2b)"><path class="q535g5bjz"/><path fill="url(#igxsBIe)" class="k0ryxwb-p"/></g><path fill="url(#ir5nDOd)" class="zc3il9uqy"/><path fill="url(#i2xGyJU)" class="zc3il9uqy"/><g filter="url(#ix7Oc0d)"><path fill="url(#iGGfoLc)" class="et0gjibkh"/></g><g filter="url(#iATeewd)"><path fill="url(#i18nY5d)" class="g-8fwc25r"/></g><g filter="url(#iu3x4Mc)"><path stroke="url(#iqcipDc)" class="tl8qpbpot"/></g><g filter="url(#iD0NSOc)"><path stroke="url(#i16r88c)" class="raxopjbju"/></g><g filter="url(#iPm14sd)"><path stroke="url(#iB5oHnb)" class="tt72geb2m"/></g><path fill="url(#iOhggTZ)" class="e_-jof7ml"/><path fill="url(#i19yhLx)" class="vk550_n8r"/><g filter="url(#ib93AQu)"><path fill="url(#iQDEVVd)" class="yku2xwbej"/></g><g filter="url(#iBxCwje)"><path fill="url(#iREbeJe)" class="miej57zij"/></g><g filter="url(#iqGjjJd)"><path fill="url(#iQz0kPc)" class="e74bonnxr"/><path fill="url(#iePurxd)" class="e74bonnxr"/></g><g filter="url(#i7vEA7b)"><path class="lwk1-mbqs"/><path fill="url(#iTHZGQc)" class="pgpm56tyt"/></g><g filter="url(#iyLFiCe)"><path class="z18nffrim"/><path fill="url(#iDi23vc)" class="yoj1htbxp"/></g><g filter="url(#iCZmscc)"><path fill="url(#iVR8p0b)" class="x8bj1f6ut"/><path fill="url(#ic6xJsd)" class="x8bj1f6ut"/><path fill="url(#iUEdI8b)" class="x8bj1f6ut"/><path fill="url(#i1Rzk7Z)" class="x8bj1f6ut"/><path fill="url(#iTKlkjd)" class="x8bj1f6ut"/><path fill="url(#isJMM3b)" class="x8bj1f6ut"/><path fill="url(#igNQ4Ib)" class="x8bj1f6ut"/></g><path fill="url(#ifG2mkb)" class="x8bj1f6ut"/><path fill="url(#iGK8MQd)" class="x8bj1f6ut"/><g filter="url(#iLNcVLM)"><path class="f-ewu1axu"/></g><g filter="url(#i0vUPNb)"><path class="d_rswwr6d"/><path fill="url(#iwjtymb)" class="bn1ilc5ze"/><path fill="url(#i2zVtyb)" class="bn1ilc5ze"/><path fill="url(#icLqite)" class="bn1ilc5ze"/><path fill="url(#icYewbd)" class="bn1ilc5ze"/></g><g filter="url(#ibzkqja)"><path stroke="url(#iSZBq3c)" class="hgyvl05np"/></g><path class="j0yqg2gml"/><g filter="url(#iOuNlIb)"><path class="s4q9vpbdz"/></g><g filter="url(#iTV2dUc)"><path class="efv-2ccyb"/></g><g filter="url(#ipvTKDb)"><path class="dwq2u1s1w"/></g><g filter="url(#i5GGeIe)"><path clip-rule="evenodd" class="wnr93abcy"/></g><path class="u8uao1bcq"/><path fill="url(#i8Bc8Ad)" class="w270qkb5v"/><path class="dp9cizbsg"/><g filter="url(#i90jfWy)"><path class="xckf85eqw"/><path fill="url(#ic0BPtd)" class="kj0gkk02b"/></g><g filter="url(#iXUl6vT)"><path fill="url(#ijgb1Pb)" class="huvgmobvs"/></g><path class="dvdov_bqj"/><path fill="url(#i4HUjud)" class="w3czi2bny"/><path class="njw83hasq"/><g filter="url(#iLnbcQb)"><path fill="url(#it4gQYb)" class="xdb_9ub9g"/></g><g filter="url(#iQtorud)"><ellipse transform="rotate(-27.914 16.064 8.885)" class="g6iiqntqd"/><ellipse fill="url(#iWFkSnd)" transform="rotate(-27.914 16.064 8.885)" class="u-0nwjnae"/></g><g filter="url(#iDruFRM)"><path class="geoxmeb1t"/></g><g filter="url(#iOt3eMd)"><path class="yjag_ob6k"/></g><g filter="url(#i9cLZFb)"><path class="jb0im_brr"/><path fill="url(#iYdWV2b)" class="b1kjk2bqp"/></g><g filter="url(#iHWyb0b)"><path class="wf63vlbpy"/><path fill="url(#iHYcnXb)" class="dopti1byn"/><path fill="url(#ivqKFrd)" class="dopti1byn"/></g><g filter="url(#iF8qSne)"><path stroke="url(#i2cSwbb)" class="a8v6ombcy"/></g><g filter="url(#iUjfiac)"><path class="t40zwkn-u"/></g><defs><radialGradient id="iOQ8Zae" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 3.855 13.704)scale(4.02427 5.02713)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ixa2hWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52282 1.7014 -2.23552 -3.31479 15.482 11.915)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iLL68lb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14403 1.49606 -1.14877 -.87846 13.972 9.686)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iG2mDDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12939 1.84805 -1.3018 -.79555 14.367 7.91)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="imIaxEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20271 2.28808 -3.1762 1.66955 15.13 2.44)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iH6ryxQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2613 1.26139 -1.76277 -1.76264 23.314 4.259)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i3B1LBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61332 .46935 -.9788 -3.36445 24.781 8.747)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ivNHvJt" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.404 7.362)scale(2.53986 3.2354)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iITlE0g" cx="0" cy="0" r="1" gradientTransform="matrix(-.79144 -2.31914 1.8343 -.62599 22.352 6.617)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iH3BIgM" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -76.896 127.06)scale(1.32324 2.14404)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iJls1sc" cx="0" cy="0" r="1" gradientTransform="rotate(143.412 5.637 14.178)scale(5.96846 3.36558)" gradientUnits="userSpaceOnUse"><stop class="s2ayxoxhu"/><stop offset="1" class="j6izx0btu"/></radialGradient><radialGradient id="iKpeIKe" cx="0" cy="0" r="1" gradientTransform="rotate(117.506 5.31 14.348)scale(10.2174 6.6572)" gradientUnits="userSpaceOnUse"><stop class="c9qnqxb4v"/><stop offset="1" class="f6lyc94ec"/></radialGradient><radialGradient id="iW1L1sc" cx="0" cy="0" r="1" gradientTransform="rotate(133.238 6.288 9.66)scale(4.31097 4.07134)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="abn8efjgi"/><stop offset="1" class="v46c2zbrf"/></radialGradient><radialGradient id="iUkKPae" cx="0" cy="0" r="1" gradientTransform="rotate(-144.77 15.76 10.464)scale(4.37936 1.86088)" gradientUnits="userSpaceOnUse"><stop class="jhjy8fbuk"/><stop offset="1" class="eb_-_cbgw"/></radialGradient><radialGradient id="is3wVfe" cx="0" cy="0" r="1" gradientTransform="rotate(-140.774 9.446 11.601)scale(.98834 .87647)" gradientUnits="userSpaceOnUse"><stop class="ui2onhbah"/><stop offset="1" class="r9xs6qbkj"/></radialGradient><radialGradient id="isUixxc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 .23438 -.1603 .3847 13.134 19.474)" gradientUnits="userSpaceOnUse"><stop class="i5_a4vbjv"/><stop offset="1" class="qromo9b3v"/></radialGradient><radialGradient id="igxsBIe" cx="0" cy="0" r="1" gradientTransform="rotate(-111.297 16.984 9.897)scale(2.70865 13.4771)" gradientUnits="userSpaceOnUse"><stop class="mzqfvc6-z"/><stop offset="1" class="ustoi7qid"/></radialGradient><radialGradient id="ir5nDOd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.70754 2.1907 -2.07089 -13.90312 21.926 25.796)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="ypkr2xb-f"/><stop offset="1" class="iavdo9o2k"/></radialGradient><radialGradient id="i2xGyJU" cx="0" cy="0" r="1" gradientTransform="rotate(81.715 -8.12 19.602)scale(5.63835 23.6847)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="qku01nnzi"/><stop offset=".947" class="dpkmj1bvt"/></radialGradient><radialGradient id="iQz0kPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59872 -1.78206 2.17582 1.95197 22.156 10.345)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iePurxd" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -4.032 47.371)scale(1.31991 .37316)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iTHZGQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.32125 -.09828 .07683 1.03285 22.053 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iDi23vc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05604 0 0 -.83308 14.184 9.492)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iVR8p0b" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 9.366 6.783)scale(6.26698 8.38824)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ic6xJsd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02873 .39476 -.43575 -3.3432 21.056 10.213)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iUEdI8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.14404 -3.31479 4.20585 1.45158 16.128 15.434)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="i1Rzk7Z" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.88451 -6.81154 0 18.21 8.83)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iTKlkjd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04289 1.1859 -2.04174 -10.40395 19.794 10.535)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="isJMM3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.007 1.23586 0 20.224 8.655)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="igNQ4Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14853 1.31629 0 16.393 8.455)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ifG2mkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1247 0 0 -5.64028 22.67 9.956)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iGK8MQd" cx="0" cy="0" r="1" gradientTransform="rotate(71.834 5.546 13.137)scale(3.68387 6.41774)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iwjtymb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39863 -1.78864 .55124 -.12285 18.897 10.593)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="icYewbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68202 0 0 -.19067 18.687 10.778)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i8Bc8Ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70995 -1.12926 0 20.12 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ic0BPtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20294 -.26151 .36005 -.27941 19.92 9.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4HUjud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70996 -1.12927 0 16.3 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWFkSnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00677 -.43233 .51968 -.00814 16.05 9.161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYdWV2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.10436 -2.41118 1.2335 .56496 13.26 7.113)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iHYcnXb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.138 7.528)scale(4.2641 6.97155)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ivqKFrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.18406 1.19638 -2.57396 -.39599 18.394 2.88)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iw7DLYb" width="13.392" height="13.892" x="11.639" y="1.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="iytFOte" width="15.898" height="17.05" x="7.699" y="13.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.345098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.396078 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3484" result="effect2_innerShadow_4002_3484"/></filter><filter id="iKlkkGe" width="15.258" height="14.494" x="7.185" y="15.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".25"/></filter><filter id="iM74y2b" width="14.977" height="12.277" x="7.219" y="17.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.556863 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="ix7Oc0d" width="4.354" height="4.526" x="18.596" y="15.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.27451 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="iATeewd" width="3.759" height="5.328" x="19.426" y="15.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".5"/></filter><filter id="iu3x4Mc" width="1.206" height=".37" x="7.769" y="26.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="iD0NSOc" width="1.261" height=".3" x="7.535" y="27.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="iPm14sd" width="1.206" height=".3" x="7.945" y="28.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="ib93AQu" width="4.908" height="6.063" x="16.822" y="19.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".25"/></filter><filter id="iBxCwje" width="2.966" height="2.816" x="12.702" y="8.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="iqGjjJd" width="2.816" height="3.066" x="21.026" y="7.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="i7vEA7b" width="2.88" height="2.88" x="20.995" y="8.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".25"/></filter><filter id="iyLFiCe" width="2.68" height="2.68" x="12.787" y="8.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".2"/></filter><filter id="iCZmscc" width="8.918" height="9.918" x="13.752" y="5.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="iLNcVLM" width="2.643" height="3.347" x="16.747" y="8.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".25"/></filter><filter id="i0vUPNb" width="2.143" height="2.847" x="17.139" y="8.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".125"/></filter><filter id="ibzkqja" width="3.29" height="1.385" x="16.566" y="11.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="iOuNlIb" width="2.651" height="1.125" x="19.01" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="iTV2dUc" width="2.651" height="1.125" x="14.76" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="ipvTKDb" width="2.171" height=".98" x="14.878" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="i5GGeIe" width="2.171" height=".98" x="19.618" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/></filter><filter id="i90jfWy" width=".714" height=".635" x="19.465" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="iXUl6vT" width=".83" height=".849" x="20.187" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".1"/></filter><filter id="iLnbcQb" width=".913" height=".96" x="16.299" y="8.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".1"/></filter><filter id="iQtorud" width=".824" height=".641" x="15.652" y="8.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".05"/></filter><filter id="iDruFRM" width="2.053" height=".931" x="19.608" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".1"/></filter><filter id="iOt3eMd" width="2.053" height=".931" x="14.837" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".1"/></filter><filter id="i9cLZFb" width="3.786" height="4.05" x="12.7" y="3.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/><feGaussianBlur result="effect2_foregroundBlur_4002_3484" stdDeviation=".15"/></filter><filter id="iHWyb0b" width="7.741" height="5.122" x="15.399" y="2.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3484"/><feGaussianBlur result="effect2_foregroundBlur_4002_3484" stdDeviation=".125"/></filter><filter id="iF8qSne" width="1.077" height="2.096" x="15.38" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".1"/></filter><filter id="iUjfiac" width="5.812" height="3.138" x="17.608" y="4.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3484" stdDeviation=".375"/></filter><linearGradient id="ieTn7Mb" x1="22.317" x2="16.362" y1="3.408" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i1gsgse" x1="20.114" x2="12.395" y1="27.89" y2="19.39" gradientUnits="userSpaceOnUse"><stop class="pokolfbgc"/><stop offset="1" class="b3y8h4ksz"/></linearGradient><linearGradient id="i8XiPOe" x1="16.52" x2="16.52" y1="29.971" y2="27.26" gradientUnits="userSpaceOnUse"><stop class="ckcj4hbsb"/><stop offset="1" class="q93oiybtq"/></linearGradient><linearGradient id="iMgi8Bd" x1="19.165" x2="11.447" y1="17.603" y2="26.103" gradientUnits="userSpaceOnUse"><stop class="tts0ot_3n"/><stop offset="1" class="luw3gnblf"/></linearGradient><linearGradient id="iGGfoLc" x1="21.848" x2="18.973" y1="18.201" y2="18.045" gradientUnits="userSpaceOnUse"><stop class="a_ut7cc2e"/><stop offset="1" class="cyj659bzg"/></linearGradient><linearGradient id="i18nY5d" x1="21.317" x2="20.614" y1="16.452" y2="20.952" gradientUnits="userSpaceOnUse"><stop class="gla1f_2eg"/><stop offset="1" class="fx7b7_wnc"/></linearGradient><linearGradient id="iqcipDc" x1="7.919" x2="9.075" y1="27.132" y2="27.202" gradientUnits="userSpaceOnUse"><stop class="m60z_b3pe"/><stop offset="1" class="oc8qfqb2f"/></linearGradient><linearGradient id="i16r88c" x1="7.685" x2="8.915" y1="28.116" y2="28.122" gradientUnits="userSpaceOnUse"><stop class="m60z_b3pe"/><stop offset="1" class="oc8qfqb2f"/></linearGradient><linearGradient id="iB5oHnb" x1="8.095" x2="9.255" y1="29.03" y2="29.035" gradientUnits="userSpaceOnUse"><stop class="m60z_b3pe"/><stop offset="1" class="oc8qfqb2f"/></linearGradient><linearGradient id="iOhggTZ" x1="11.931" x2="24.521" y1="13.699" y2="13.699" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i19yhLx" x1="11.931" x2="24.521" y1="13.672" y2="13.672" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iQDEVVd" x1="20.447" x2="16.056" y1="20.166" y2="26.244" gradientUnits="userSpaceOnUse"><stop class="ass3y7bac"/><stop offset="1" class="z_hjike1x"/></linearGradient><linearGradient id="iREbeJe" x1="12.702" x2="15.292" y1="9.567" y2="9.567" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i2zVtyb" x1="17.389" x2="18.21" y1="10.657" y2="10.657" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="icLqite" x1="18.21" x2="18.21" y1="11.356" y2="10.822" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iSZBq3c" x1="17.279" x2="17.682" y1="12.589" y2="11.966" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ijgb1Pb" x1="20.8" x2="20.526" y1="9.017" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it4gQYb" x1="16.952" x2="16.677" y1="9.016" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2cSwbb" x1="15.68" x2="16.157" y1="4.067" y2="5.182" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-woman-light" /></template>
<style>
.a_ut7cc2e {
  stop-color: var(--svg-color--8e6acb, #8E6ACB);
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a8v6ombcy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.68 3.767c.02.212.206 1.012.477 1.496");
}

.abn8efjgi {
  stop-color: var(--svg-color--513091, #513091);
}

.ass3y7bac {
  stop-color: var(--svg-color--f7caba, #F7CABA);
}

.b1kjk2bqp {
  d: path("M13.775 4.25c.495-.523 1.431-.524 1.864-.446l.346 1.13c-.22-.035-.418.043-.584.205c-.392 1.103-1.74 1.71-2.366 1.877c-.13-1.305.095-2.083.74-2.765");
}

.b3y8h4ksz {
  stop-color: var(--svg-color--7657b1, #7657B1);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bn1ilc5ze {
  d: path("m17.876 9.176l-.465 1.488a.472.472 0 0 0 .455.611h.688c.323 0 .55-.31.456-.611l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c9qnqxb4v {
  stop-color: var(--svg-color--9c7cd3, #9C7CD3);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckcj4hbsb {
  stop-color: var(--svg-color--5d4097, #5D4097);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.d_rswwr6d {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m17.876 9.176l-.465 1.488a.472.472 0 0 0 .455.611h.688c.323 0 .55-.31.456-.611l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dopti1byn {
  d: path("M17.682 2.674c-.99-.219-1.88.77-1.983 1.137c.92 3.102 3.249 2.932 5.548 2.676c1.376-.153 1.525.475 1.642.778c0-3.442-2.926-4.088-5.182-4.586z");
}

.dp9cizbsg {
  fill: var(--svg-color--000, #000);
  d: path("M19.674 9.333c0-.248.199-.447.448-.447a.445.445 0 0 1 .397.653h-.791a.4.4 0 0 1-.054-.206");
}

.dpkmj1bvt {
  stop-color: var(--svg-color--c08895, #C08895);
}

.dvdov_bqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.118 8.313c-.571 0-1.054.394-1.186.927a.24.24 0 0 0 .235.298h1.952a.2.2 0 0 0 .199-.238a1.226 1.226 0 0 0-1.2-.987");
}

.dwq2u1s1w {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m15.237 7.935l-.004.003a.235.235 0 0 1-.24-.403l.003-.002l.008-.005l.029-.016l.101-.051c.086-.041.21-.094.36-.142a2.45 2.45 0 0 1 1.161-.095a.235.235 0 0 1-.081.462c-.35-.062-.684 0-.938.08a2.4 2.4 0 0 0-.399.17");
}

.e_-jof7ml {
  d: path("M18.534 13.673q.331.015.675.044a17 17 0 0 0-.675-.044");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e74bonnxr {
  d: path("M22.434 10.9a1.408 1.408 0 1 0 0-2.817a1.408 1.408 0 0 0 0 2.816");
}

.eb_-_cbgw {
  stop-color: var(--svg-color--6f56b0, #6F56B0);
  stop-opacity: 0;
}

.efv-2ccyb {
  fill: var(--svg-color--272528, #272528);
  d: path("M17.211 8.994c-.232-.409-.585-.731-1.345-.731a1.45 1.45 0 0 0-.939.322c-.235.19-.204.434-.021.525l.486.278c.57-.185 1.201-.21 1.82-.394");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.et0gjibkh {
  d: path("M19.045 17.51c0-1.562 1.203-1.887 1.805-1.855c.8 0 1.747.576 1.698 1.962a10.4 10.4 0 0 1-.351 2.362h-3.601c.15-.491.449-1.673.449-2.47");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f-ewu1axu {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m17.867 9.297l-.598 1.488a.472.472 0 0 0 .455.612h.688c.323 0 .55-.311.456-.612l-.465-1.488c-.1-.33-.432-.33-.536 0");
}

.f6lyc94ec {
  stop-color: var(--svg-color--8563c2, #8563C2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fx7b7_wnc {
  stop-color: var(--svg-color--a281e0, #A281E0);
  stop-opacity: 0;
}

.g-8fwc25r {
  d: path("M20.703 17.171a35 35 0 0 1-.277 2.61h1.5c.149-.873.224-1.863.258-2.58a.72.72 0 0 0-.725-.749a.764.764 0 0 0-.756.72");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6iiqntqd {
  cx: 16.064px;
  cy: 8.885px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.341px;
  ry: 0.173px;
}

.geoxmeb1t {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.908 7.415c.282-.069.984-.034 1.453.301");
}

.gla1f_2eg {
  stop-color: var(--svg-color--a281e0, #A281E0);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hgyvl05np {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.21 12.04a2.65 2.65 0 0 1-1.244-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.077-.119-.055-.256-.178-.192c-.36.192-.783.302-1.244.302Z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.huvgmobvs {
  d: path("M20.817 9.23a.74.74 0 0 0-.202-.405l-.228.25l.103.2z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i5_a4vbjv {
  stop-color: var(--svg-color--725e92, #725E92);
}

.iavdo9o2k {
  stop-color: var(--svg-color--d6a493, #D6A493);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ix50_xb6d {
  d: path("M13.488 16.186c.687-.874 2.474-2.374 3.281-3.015h3.266c2.15.587 2.562 2.625 2.562 3.625v11.328c0 1.563-1.208 1.88-1.812 1.844h-9.89c-2.282 0-4.094-3.188-2.72-6.61c1.264-2.63 3.503-3.447 4.787-3.74a.16.16 0 0 0 .093-.243c-.98-1.43-.39-2.141.433-3.189");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j0yqg2gml {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M18.21 12.04a2.65 2.65 0 0 1-1.244-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.077-.119-.055-.256-.178-.192c-.36.192-.783.302-1.244.302");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6izx0btu {
  stop-color: var(--svg-color--755fa5, #755FA5);
  stop-opacity: 0;
}

.jb0im_brr {
  fill: var(--svg-color--232121, #232121);
  d: path("M13.775 4.25c.495-.523 1.431-.524 1.864-.446l.346 1.13c-.22-.035-.418.043-.584.205c-.392 1.103-1.74 1.71-2.366 1.877c-.13-1.305.095-2.083.74-2.765");
}

.jhjy8fbuk {
  stop-color: var(--svg-color--7a63b9, #7A63B9);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k0ryxwb-p {
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l2.702-2.005l.752 2.307c-.664 2.752-2.039 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.433a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.405a.49.49 0 0 1 .16-.512a.48.48 0 0 1-.385-.547c.037-.424.427-.483.64-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kj0gkk02b {
  d: path("M20.064 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.056-.074.007-.215.139-.314c.132-.098.284-.118.34-.044");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.luw3gnblf {
  stop-color: var(--svg-color--584487, #584487);
}

.lwk1-mbqs {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M22.435 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.m60z_b3pe {
  stop-color: var(--svg-color--cb947f, #CB947F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.miej57zij {
  d: path("M14.11 10.9a1.408 1.408 0 1 0 0-2.817a1.408 1.408 0 0 0 0 2.816");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzqfvc6-z {
  stop-color: var(--svg-color--e1adac, #E1ADAC);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n6lo_jd-m {
  fill-rule: evenodd;
  d: path("M24.498 10.726a2.84 2.84 0 0 0 .283-1.25a2.9 2.9 0 0 0-.235-1.141h.005a3 3 0 0 0-.246-.45l-.002-.002c-.301-.46-.46-1-.46-1.55v-.009a2.89 2.89 0 0 0-2.887-2.887c-.16 0-.31-.07-.399-.203a2.9 2.9 0 0 0-2.347-1.205c-.965 0-1.824.478-2.347 1.205a.5.5 0 0 1-.398.203l-.075.001a2.887 2.887 0 0 0-2.812 2.886v.01c0 .548-.16 1.088-.46 1.549l-.002.003a2.89 2.89 0 0 0-.193 2.84a.45.45 0 0 1 0 .398a2.812 2.812 0 0 0 2.533 4.047h7.51a2.812 2.812 0 0 0 2.532-4.047a.45.45 0 0 1 0-.398M13.769 8.387h-.01l1.048 2.061c.108 2.453 1.066 0 3.403 0c2.338 0 3.357 2.73 3.465.278l.994-2.798c-.047-1.09-.836-1.166-.994-1.166h-2.818a3.38 3.38 0 0 1-2.79-1.464a.23.23 0 0 0-.404.045l-.072.17a2.02 2.02 0 0 1-1.04 1.08q-.021.006-.046.017l-.045.018c-.206.107-.69.429-.709 1.26l.01.267z");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.njw83hasq {
  fill: var(--svg-color--000, #000);
  d: path("M16.746 9.333a.445.445 0 0 0-.447-.447a.445.445 0 0 0-.397.653h.791a.44.44 0 0 0 .053-.206");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.oc8qfqb2f {
  stop-color: var(--svg-color--cb947f, #CB947F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohgemac2l {
  d: path("M20.339 16.167c-.568-.03-1.704.276-1.704 1.75c0 .752-.283 1.867-.424 2.33h.059c-.527 1.723-2.32 4.875-6.387 5.905c-.765.139-1.032-.064-1.428-.525a28 28 0 0 0-.348-.396a.52.52 0 0 0-.748-.024a.52.52 0 0 0-.048.7c.093.115.187.227.256.299a5.5 5.5 0 0 1-1.01-.1c-.534-.11-.697.249-.718.373c-.026.153 1.516.324 1.76.416c-.201-.009-.569.046-.604.447a.455.455 0 0 0 .364.516c-.069.054-1.741.317-1.672.57c.1.363.424.382.543.382a.43.43 0 0 0-.17.434c.05.31.396.409.594.409h.048c.52.015 4.622.128 8.21-2.358c2.773-2.147 4.072-4.422 4.698-7.02l-.288-.027h.288a9.8 9.8 0 0 0 .332-2.23c.046-1.308-.848-1.85-1.603-1.85");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgpm56tyt {
  d: path("M22.435 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pokolfbgc {
  stop-color: var(--svg-color--7a61b9, #7A61B9);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.q535g5bjz {
  fill: var(--svg-color--e4b4a1, #E4B4A1);
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l2.702-2.005l.752 2.307c-.664 2.752-2.039 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.433a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.405a.49.49 0 0 1 .16-.512a.48.48 0 0 1-.385-.547c.037-.424.427-.483.64-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

.q93oiybtq {
  stop-color: var(--svg-color--5d4097, #5D4097);
  stop-opacity: 0;
}

.qku01nnzi {
  stop-color: var(--svg-color--c08895, #C08895);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qromo9b3v {
  stop-color: var(--svg-color--725e92, #725E92);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r9xs6qbkj {
  stop-color: var(--svg-color--423363, #423363);
  stop-opacity: 0;
}

.raxopjbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.685 28.116h.96");
}

.s2ayxoxhu {
  stop-color: var(--svg-color--755fa5, #755FA5);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s4q9vpbdz {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M19.21 8.994c.232-.409.585-.731 1.345-.731c.333 0 .654.092.939.322c.235.19.204.434.021.525l-.486.278c-.57-.185-1.201-.21-1.82-.394");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t40zwkn-u {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m20.316 5.833l-1.247.23a.602.602 0 1 1-.11-1.195h2.049c1.211 0 1.612 1.221 1.661 1.638a2.75 2.75 0 0 0-2.353-.673");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tl8qpbpot {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.92 27.132c.174.013.6.045.906.07");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tt72geb2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.095 29.03h.906");
}

.tts0ot_3n {
  stop-color: var(--svg-color--553697, #553697);
}

.u-0nwjnae {
  cx: 16.064px;
  cy: 8.885px;
  rx: 0.341px;
  ry: 0.173px;
}

.u8uao1bcq {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.303 8.313c.571 0 1.054.394 1.185.927a.24.24 0 0 1-.234.298h-1.952a.2.2 0 0 1-.2-.238c.11-.56.604-.987 1.2-.987");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ui2onhbah {
  stop-color: var(--svg-color--423363, #423363);
}

.ustoi7qid {
  stop-color: var(--svg-color--e1adac, #E1ADAC);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v46c2zbrf {
  stop-color: var(--svg-color--785cad, #785CAD);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vk550_n8r {
  d: path("M18.245 13.673h-.035c.088 0 .166 0 .254.009c-.07-.01-.149-.01-.219-.01");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w270qkb5v {
  d: path("M20.122 8.552a.78.78 0 0 1 .752.987h-1.509a.784.784 0 0 1 .756-.987");
}

.w3czi2bny {
  d: path("M16.3 8.552a.78.78 0 0 0-.754.987h1.51a.786.786 0 0 0-.756-.987");
}

.wf63vlbpy {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M17.682 2.674c-.99-.219-1.88.77-1.983 1.137c.92 3.102 3.249 2.932 5.548 2.676c1.376-.153 1.525.475 1.642.778c0-3.442-2.926-4.088-5.182-4.586z");
}

.wnr93abcy {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m21.476 7.535l-.121.201za.235.235 0 0 1-.24.402l-.005-.003a1 1 0 0 0-.099-.05a2.4 2.4 0 0 0-.3-.119a2 2 0 0 0-.937-.08a.235.235 0 1 1-.082-.462c.45-.08.865 0 1.163.095a3 3 0 0 1 .488.209l.009.005l.002.001z");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x8bj1f6ut {
  d: path("M13.759 8.386h.01l-.008-.232l-.01-.268c.019-.83.503-1.152.71-1.259l.044-.018l.045-.017a2.02 2.02 0 0 0 1.041-1.08l.072-.17a.23.23 0 0 1 .404-.045a3.38 3.38 0 0 0 2.79 1.464h2.818c.158 0 .947.077.994 1.166l-.104 2.69c-.108 2.451-2.023 4.098-4.36 4.098s-4.253-1.647-4.361-4.099z");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xckf85eqw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.064 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.056-.074.007-.215.139-.314c.132-.098.284-.118.34-.044");
}

.xdb_9ub9g {
  d: path("M17.013 9.241c0-.252-.206-.42-.261-.471l-.252.244l.155.316z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.yjag_ob6k {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.59 7.415c-.282-.069-.984-.034-1.453.301");
}

.yku2xwbej {
  d: path("M20.355 20.166c-.463 2.15-2.258 4.287-3.033 5.063c2.637-1.776 3.746-4.13 3.908-5.063z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yoj1htbxp {
  d: path("M14.127 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.ypkr2xb-f {
  stop-color: var(--svg-color--d6a493, #D6A493);
  stop-opacity: 0;
}

.z_hjike1x {
  stop-color: var(--svg-color--f7caba, #F7CABA);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z18nffrim {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M14.127 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zc3il9uqy {
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l3.454.302c-.664 2.752-2.039 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.432a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.406a.49.49 0 0 1 .16-.512a.48.48 0 0 1-.385-.546c.037-.425.427-.483.64-.474c-.259-.097-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

</style>
