<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#iePIJpe)"><path class="vmc2k3zbd"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iz0Xh1c)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="htxp2lohr"/><path fill="url(#iaSWI7d)" class="htxp2lohr"/><path fill="url(#ihSlXYc)" class="htxp2lohr"/><g filter="url(#ibkQmbb)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#iZxjnGc)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#ix6vz4b)" class="jdcv0xbln"/><g filter="url(#ipG49ee)"><path fill="url(#iW7wXdk)" class="vnlonib2h"/><path fill="url(#isch8eb)" class="vnlonib2h"/></g><g filter="url(#ic0fbQK)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#iVbv2NI)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><g filter="url(#iuVG7te)"><circle fill="url(#iXvIvrc)" class="tqj3mfarw"/></g><g filter="url(#i7CUH0d)"><circle fill="url(#ipL0zqb)" class="ho6_1fbmc"/></g><g filter="url(#iMbCctf)"><circle fill="url(#iBaXsXd)" class="af47qnbed"/><circle fill="url(#iX6rtFs)" class="af47qnbed"/></g><g filter="url(#ivjFBuG)"><circle class="ofo8oub9i"/><circle fill="url(#itJK8kb)" class="bq6gubb9b"/><circle fill="url(#ijAa2Cb)" class="bq6gubb9b"/></g><g filter="url(#i0lCDYc)"><path fill="url(#ig2KMBu)" class="hdbmbom4a"/><path fill="url(#iVDOaQe)" class="hdbmbom4a"/><path fill="url(#i7Scy3c)" class="hdbmbom4a"/><path fill="url(#iYaZmfd)" class="hdbmbom4a"/><path fill="url(#iSJtCFX)" class="hdbmbom4a"/><path fill="url(#iW6vtJe)" class="hdbmbom4a"/><path fill="url(#iSsCbvc)" class="hdbmbom4a"/></g><g filter="url(#iXMn3oe)"><path class="yc0qc5bfz"/><path fill="url(#iLGP1QU)" class="dqe-d-rgv"/><path fill="url(#iWykuWd)" class="dqe-d-rgv"/><path fill="url(#iVRjkge)" class="dqe-d-rgv"/><path fill="url(#if9l01d)" class="dqe-d-rgv"/></g><g filter="url(#i7IY1kc)"><path class="tg4vrccsv"/></g><g filter="url(#i4tasxe)"><path class="e-iq_i24d"/><path fill="url(#iJo1EQb)" class="y0jvqtbxh"/><path fill="url(#iYeDLpc)" class="y0jvqtbxh"/><path fill="url(#iOgpMbb)" class="y0jvqtbxh"/><path fill="url(#iJl9fPc)" class="y0jvqtbxh"/></g><g filter="url(#i8AoPPb)"><path fill="url(#i3KaKsb)" class="ykeqlablp"/></g><path stroke="url(#i9DlXje)" class="tgrdhvbah"/><path class="mnvvlw7_k"/><path fill="url(#i1ILhSb)" class="ef2daacsc"/><path class="skpn_ly8l"/><g filter="url(#iFvWnwd)"><path class="d6-8jybix"/><path fill="url(#ilKcVde)" class="byoa83brt"/></g><g filter="url(#ifljiLg)"><path fill="url(#igXE6hb)" class="j-372xbis"/></g><path class="zhhh3zbzr"/><path fill="url(#iSTq1Td)" class="g3r_1p52s"/><path class="o_t6_vals"/><g filter="url(#iiKZoby)"><path fill="url(#iBfLjNd)" class="l_ou99l7k"/></g><g filter="url(#iisX7fe)"><ellipse transform="rotate(-27.914 13.138 11.944)" class="e6frhkbcu"/><ellipse fill="url(#iNLO3Cc)" transform="rotate(-27.914 13.138 11.944)" class="lsv-gob5y"/></g><g filter="url(#ip9KDKc)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#ienGn9b)"><path class="trw5-7ral"/></g><g filter="url(#iojHuxc)"><path fill="url(#iagoo5c)" class="rouoh6bhy"/></g><g filter="url(#iXu66SG)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#izIFE5d)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#iHNbxZd)"><path fill="url(#iuApGId)" clip-rule="evenodd" class="wfsof20kz"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="wfsof20kz"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="wfsof20kz"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="ix6vz4b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iW7wXdk" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="avdlipbug"/><stop offset="1" class="vjhqa-bnq"/></radialGradient><radialGradient id="isch8eb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="v6yinkbrb"/><stop offset="1" class="lit-3eb_c"/></radialGradient><radialGradient id="iXvIvrc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01634 0 0 3.52862 8.585 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iX6rtFs" cx="0" cy="0" r="1" gradientTransform="matrix(.94989 -.69165 .78944 1.08418 21.862 12.532)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="itJK8kb" cx="0" cy="0" r="1" gradientTransform="matrix(.94363 -1.7356 1.01585 .55231 21.387 13.781)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ijAa2Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38017 .38406 21.434 12.837)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="i7Scy3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.16384 -11.082 0 15.613 12.609)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iYaZmfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50184 1.84841 0 18.655 11.376)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iSJtCFX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.59811 1.98739 0 13.418 11.338)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iW6vtJe" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.618 8.714)scale(3.35843 1.97329)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iSsCbvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41424 -4.43454 0 15.992 10.87)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="t9lasebad"/><stop offset="1" class="l7k3phbox"/></radialGradient><radialGradient id="iLGP1QU" cx="0" cy="0" r="1" gradientTransform="matrix(.9167 -3.39716 1.25977 .33994 20.952 8.12)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iWykuWd" cx="0" cy="0" r="1" gradientTransform="matrix(4.39474 .40444 -.21746 2.36302 19.065 6.097)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iVRjkge" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92938 -2.98806 0 15.959 2.954)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="if9l01d" cx="0" cy="0" r="1" gradientTransform="matrix(3.53197 -2.58832 4.05504 5.53344 8.55 10.788)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iJl9fPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22624 -.72685 0 16.335 14.683)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i1ILhSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.2279 0 18.463 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="ilKcVde" cx="0" cy="0" r="1" gradientTransform="matrix(-.26641 -.3433 .47265 -.36679 18.2 12.15)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSTq1Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03778 -1.22796 0 13.45 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="iNLO3Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00889 -.56757 .68225 -.01068 13.12 12.305)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iePIJpe" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".25"/></filter><filter id="iz0Xh1c" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="ibkQmbb" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="iZxjnGc" width="3.6" height="4.539" x="15.879" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="ipG49ee" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.0666667 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="ic0fbQK" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2679" result="effect2_innerShadow_4002_2679"/></filter><filter id="iVbv2NI" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2679" result="effect2_innerShadow_4002_2679"/></filter><filter id="iuVG7te" width="4.036" height="3.836" x="8.585" y="10.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="i7CUH0d" width="3.286" height="3.286" x="8.86" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".25"/></filter><filter id="iMbCctf" width="4.086" height="4.086" x="19.516" y="10.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="ivjFBuG" width="3.286" height="3.286" x="19.791" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".25"/></filter><filter id="i0lCDYc" width="11.919" height="13.97" x="10.033" y="6.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="iXMn3oe" width="14.479" height="9.742" x="8.719" y="2.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="i7IY1kc" width="3.522" height="4.581" x="13.923" y="11.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".375"/></filter><filter id="i4tasxe" width="2.656" height="3.581" x="14.631" y="11.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".125"/></filter><filter id="i8AoPPb" width="2.656" height="3.581" x="14.631" y="11.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".125"/></filter><filter id="iFvWnwd" width=".874" height=".77" x="17.634" y="11.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".05"/></filter><filter id="ifljiLg" width=".964" height=".99" x="18.614" y="11.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".1"/></filter><filter id="iiKZoby" width="1.074" height="1.135" x="13.51" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".1"/></filter><filter id="iisX7fe" width="1.019" height=".78" x="12.628" y="11.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".05"/></filter><filter id="ip9KDKc" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><filter id="ienGn9b" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".075"/></filter><filter id="iojHuxc" width="2.624" height="2.748" x="14.643" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2679" result="effect2_innerShadow_4002_2679"/></filter><filter id="iXu66SG" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2679" result="effect2_innerShadow_4002_2679"/></filter><filter id="izIFE5d" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2679" stdDeviation=".25"/></filter><filter id="iHNbxZd" width="14.033" height="2.72" x="9.028" y="6.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2679"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="ipL0zqb" x1="10.504" x2="9.768" y1="13.158" y2="13.158" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iBaXsXd" x1="22.683" x2="21.742" y1="11.583" y2="14.497" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="ig2KMBu" x1="20.596" x2="11.822" y1="13.285" y2="14.592" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iVDOaQe" x1="9.759" x2="12.362" y1="16.383" y2="16.22" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iJo1EQb" x1="14.966" x2="16.044" y1="14.042" y2="14.042" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iYeDLpc" x1="17.037" x2="15.859" y1="14.413" y2="14.396" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iOgpMbb" x1="16.183" x2="16.183" y1="15.265" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i3KaKsb" x1="15.87" x2="15.959" y1="12.13" y2="13.425" gradientUnits="userSpaceOnUse"><stop offset=".135" class="z_7h25uvx"/><stop offset="1" class="domjs5b-x"/></linearGradient><linearGradient id="i9DlXje" x1="14.768" x2="15.267" y1="17.121" y2="16.331" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="igXE6hb" x1="19.356" x2="18.996" y1="12.115" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBfLjNd" x1="14.304" x2="13.944" y1="12.115" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iagoo5c" x1="16.899" x2="14.793" y1="4.541" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iuApGId" x1="10.974" x2="21.755" y1="7.699" y2="7.699" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer-dark" /></template>
<style>
.a2jurmb2n {
  stop-color: var(--svg-color--3183ce, #3183CE);
}

.a565onb9e {
  stop-color: var(--svg-color--33488b, #33488B);
}

.a8t42xt1y {
  stop-color: var(--svg-color--36a5fc, #36A5FC);
  stop-opacity: 0;
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.af47qnbed {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.918px;
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.avdlipbug {
  stop-color: var(--svg-color--392a3b, #392A3B);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bq6gubb9b {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.143px;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.byoa83brt {
  d: path("M18.39 11.722c.073.098-.08.217-.254.347c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.412s.373-.155.447-.058");
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d6-8jybix {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.39 11.722c.073.098-.08.217-.254.347c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.412s.373-.155.447-.058");
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.domjs5b-x {
  stop-color: var(--svg-color--3a2528, #3A2528);
  stop-opacity: 0;
}

.dqe-d-rgv {
  d: path("m21.496 5.394l.493.245c.863.43 1.356 1.41 1.171 2.452l-.678 3.493c-.06.36-.299.603-.657.612h-.02s.06-1.041.122-1.654c.05-.498-.037-.65-.493-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.98l-.185.185c-.246.183-.37.551-.37.857c.062.675.124 1.655.124 1.655q-.03 0-.057-.002a.73.73 0 0 1-.683-.61l-.678-3.494c-.123-.98.37-1.96 1.233-2.39l.493-.245c.308-.184.616-.429.924-.674l1.11-1.164c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.061 2.712.613l.924.92c.247.306.555.49.925.673");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e-iq_i24d {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e6frhkbcu {
  cx: 13.138px;
  cy: 11.944px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ef2daacsc {
  d: path("M18.465 11.506a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .993-1.296");
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

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.ft5dv1b6b {
  fill: none;
}

.g-3ft7k9f {
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g3qn2hbkl {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.727a1.406 1.406 0 0 1-2.813 0z");
}

.g3r_1p52s {
  d: path("M13.447 11.506a1.025 1.025 0 0 0-.988 1.295h1.98q.037-.131.038-.27a1.03 1.03 0 0 0-1.03-1.025");
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

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hdbmbom4a {
  d: path("m10.1 12.133l.056.002s-.062-.98-.123-1.654c0-.307.123-.675.37-.858l.184-.184c.308-.245.432-.613.432-.98v-.981c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.736.431.98c.577.405.541.627.493 1.104c-.061.613-.123 1.654-.123 1.654h.021l-.305 4.548c-.185 2.034-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.416-3.689-3.45z");
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.ho6_1fbmc {
  cx: 10.504px;
  cy: 12.837px;
  r: 1.143px;
}

.htxp2lohr {
  d: path("m17.577 29.934l-.927-5.202a.15.15 0 0 0-.147-.123h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-372xbis {
  d: path("M19.378 12.396a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j2ao_sb9l {
  d: path("M8.797 4.266c-.625.258-1.356 1.025-.969 2.375s.526 1.802.547 1.86c.04.166.223.5.633.5h.39a.46.46 0 0 0 .301-.134c.142-.134 2.254-1.596 5.827-1.718c3.645.122 6.633 1.584 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.116-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.l_ou99l7k {
  d: path("M14.384 12.41c0-.331-.27-.552-.343-.619l-.33.32l.203.416z");
}

.l7k3phbox {
  stop-color: var(--svg-color--331f25, #331F25);
  stop-opacity: 0;
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lit-3eb_c {
  stop-color: var(--svg-color--372138, #372138);
  stop-opacity: 0;
}

.lsv-gob5y {
  cx: 13.138px;
  cy: 11.944px;
  rx: 0.448px;
  ry: 0.227px;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
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

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mnvvlw7_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 11.193c.75 0 1.384.517 1.556 1.216a.315.315 0 0 1-.308.392h-2.563a.264.264 0 0 1-.26-.312a1.606 1.606 0 0 1 1.575-1.296");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n4wew7txz {
  stop-color: var(--svg-color--553830, #553830);
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.o_t6_vals {
  fill: var(--svg-color--000, #000);
  d: path("M14.034 12.53a.585.585 0 0 0-.587-.586a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
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

.ofo8oub9i {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.143px;
  fill: var(--svg-color--463133, #463133);
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rouoh6bhy {
  d: path("M14.793 3.756v.922a1.187 1.187 0 0 0 2.374 0v-.923a.2.2 0 0 0-.308-.169l-.252.16a.1.1 0 0 1-.134-.025l-.295-.402a.25.25 0 0 0-.403.001l-.292.4a.1.1 0 0 1-.135.026l-.247-.158a.2.2 0 0 0-.308.168");
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.skpn_ly8l {
  fill: var(--svg-color--000, #000);
  d: path("M17.878 12.53c0-.325.26-.586.587-.586a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.t9lasebad {
  stop-color: var(--svg-color--331f25, #331F25);
}

.t9xlhbbtl {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
}

.tg4vrccsv {
  fill: var(--svg-color--332024, #332024);
  d: path("M15.643 12.697L14.7 14.65c-.117.401.164.803.56.803h.848c.397 0 .678-.408.56-.803l-.572-1.953c-.122-.433-.325-.433-.453 0");
}

.tgrdhvbah {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.39 16.012a3.4 3.4 0 0 0 1.569.372c.581 0 1.115-.136 1.568-.372a.23.23 0 0 1 .27.044a.21.21 0 0 1 .023.268m-3.43-.312l3.388.284m-3.387-.284a.226.226 0 0 0-.27.046a.21.21 0 0 0-.022.266m.292-.312l-.25.284m3.679.028l-.042-.028m.042.028l-.042-.028m.042.028a2.23 2.23 0 0 1-1.861.994c-.78 0-1.466-.397-1.86-.994m3.679-.028a2.17 2.17 0 0 1-1.819.972a2.17 2.17 0 0 1-1.819-.972m-.041.028l.041-.028m-.041.028l.041-.028");
}

.thtcysb5g {
  d: path("M8.055 29.934H3.862a12.15 12.15 0 0 1 4.193-8.309z");
}

.tp8jvfpml {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
  stop-opacity: 0;
}

.tqj3mfarw {
  cx: 10.504px;
  cy: 12.837px;
  r: 1.918px;
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

.u5b_qpb1y {
  stop-color: var(--svg-color--734d45, #734D45);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v6yinkbrb {
  stop-color: var(--svg-color--372138, #372138);
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vjhqa-bnq {
  stop-color: var(--svg-color--301a23, #301A23);
}

.vmc2k3zbd {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.203c.04.08.12.129.208.129h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.243l.764-3.8z");
}

.vnlonib2h {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.652 2.145-2.223l-2.145-.332z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wfsof20kz {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.855-9.999-.764-11.82-.011a.775.775 0 1 1-.592-1.433c2.085-.862 7.432-2.032 12.945-.011a.775.775 0 1 1-.533 1.455");
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y0jvqtbxh {
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.yc0qc5bfz {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m21.496 5.394l.493.245c.863.43 1.356 1.41 1.171 2.452l-.678 3.493c-.06.36-.299.603-.657.612h-.02s.06-1.041.122-1.654c.05-.498-.037-.65-.493-1.103c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.98l-.185.185c-.246.183-.37.551-.37.857c.062.675.124 1.655.124 1.655q-.03 0-.057-.002a.73.73 0 0 1-.683-.61l-.678-3.494c-.123-.98.37-1.96 1.233-2.39l.493-.245c.308-.184.616-.429.924-.674l1.11-1.164c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.061 2.712.613l.924.92c.247.306.555.49.925.673");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ykeqlablp {
  d: path("m15.52 12.455l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.952c-.132-.433-.742-.433-.88 0");
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z_7h25uvx {
  stop-color: var(--svg-color--3a2528, #3A2528);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhhh3zbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.21 11.193c-.75 0-1.385.517-1.557 1.216c-.051.2.102.392.308.392h2.563c.163 0 .293-.15.26-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
