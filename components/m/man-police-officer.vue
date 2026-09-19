<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dee3snbxe"/><path fill="url(#i3b9cme)" class="g-3ft7k9f"/><path fill="url(#iT6XAqe)" class="g-3ft7k9f"/><path fill="url(#iTFqkvb)" class="g-3ft7k9f"/><path fill="url(#i6dLLtb)" class="g-3ft7k9f"/><g filter="url(#iFFrXxB)"><path class="w4srnfb7y"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iCTaZue)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#iJSlXzd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iOoOjsw)" class="htxp2lohr"/><path fill="url(#iaSWI7d)" class="htxp2lohr"/><path fill="url(#ihSlXYc)" class="htxp2lohr"/><g filter="url(#iZbIEcc)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#igmmLyc)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#ix6vz4b)" class="jdcv0xbln"/><g filter="url(#i5QOd8d)"><path fill="url(#ilmt7Yb)" class="vnlonib2h"/><path fill="url(#iSYNswc)" class="vnlonib2h"/></g><g filter="url(#iFnTVYc)"><path fill="url(#iF5yRae)" class="g3qn2hbkl"/></g><g filter="url(#iQiOEkP)"><rect fill="url(#iySt08c)" class="f5rlg0klg"/></g><circle fill="url(#iyogxjc)" class="tqj3mfarw"/><g filter="url(#i8dhbWd)"><circle fill="url(#iyvwr9c)" class="ho6_1fbmc"/></g><g filter="url(#iUPdEPc)"><circle fill="url(#i93yzTb)" class="af47qnbed"/><circle fill="url(#iBRMQ0d)" class="af47qnbed"/></g><g filter="url(#ibmDX4W)"><circle class="dn3_eabxs"/><circle fill="url(#iiz4eqc)" class="fm89bjp3t"/><circle fill="url(#ijemD5b)" class="fm89bjp3t"/></g><path fill="url(#i2T8Cgd)" class="nam0sg75y"/><path fill="url(#ih7e9Mc)" class="nam0sg75y"/><path fill="url(#iNFaRtd)" class="nam0sg75y"/><path fill="url(#iD0xIve)" class="nam0sg75y"/><path fill="url(#iuoVaIe)" class="nam0sg75y"/><path fill="url(#itw9gke)" class="nam0sg75y"/><g filter="url(#i9V0dTd)"><path class="i3ahy1b3f"/><path fill="url(#icWgY0c)" class="jc659fuoj"/><path fill="url(#iOU0gcb)" class="jc659fuoj"/><path fill="url(#izj7nre)" class="jc659fuoj"/><path fill="url(#iwWvxSV)" class="jc659fuoj"/><path fill="url(#iTNpNje)" class="jc659fuoj"/><path fill="url(#iSJoFRb)" class="jc659fuoj"/></g><path fill="url(#iCC3Lzd)" class="jc659fuoj"/><path fill="url(#iWwZUbl)" class="jc659fuoj"/><path fill="url(#irsPi6b)" class="jc659fuoj"/><g filter="url(#ijXBDmc)"><path class="z0wtlwbgo"/></g><g filter="url(#iJENCRd)"><path class="iqbcdnbik"/><path fill="url(#i2uviBb)" class="y0jvqtbxh"/><path fill="url(#imPB8Ae)" class="y0jvqtbxh"/><path fill="url(#izbencd)" class="y0jvqtbxh"/></g><g filter="url(#ihhBQEb)"><path fill="url(#iudTiAC)" class="jdr9j27so"/></g><g filter="url(#in6IDHc)"><path stroke="url(#iKD40bb)" class="rb_p-obxu"/></g><path class="dvm4z0-tz"/><path class="c7a564dhv"/><path fill="url(#iCVEN6d)" class="ef2daacsc"/><path class="skpn_ly8l"/><g filter="url(#iVUCnpb)"><path class="d6-8jybix"/><path fill="url(#inYkQsc)" class="byoa83brt"/></g><g filter="url(#iiU3gyd)"><path fill="url(#igXE6hb)" class="j-372xbis"/></g><path class="lisfvhbjo"/><path fill="url(#iUpDKid)" class="g3r_1p52s"/><path class="o_t6_vals"/><g filter="url(#inRn0HC)"><path fill="url(#iBfLjNd)" class="l_ou99l7k"/></g><g filter="url(#iuifPre)"><ellipse transform="rotate(-27.914 13.138 11.944)" class="e6frhkbcu"/><ellipse fill="url(#i139c4b)" transform="rotate(-27.914 13.138 11.944)" class="lsv-gob5y"/></g><g filter="url(#iBuAije)"><path fill="url(#isLM7wb)" class="j2ao_sb9l"/><path fill="url(#i945GOe)" class="j2ao_sb9l"/></g><path fill="url(#iizJfPb)" class="j2ao_sb9l"/><g filter="url(#icZs5Ib)"><path class="trw5-7ral"/></g><g filter="url(#ixvYg7b)"><path fill="url(#iBrxMjb)" class="nta8ypj0m"/></g><g filter="url(#iSzcDvd)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#iaq2A3b)"><path clip-rule="evenodd" class="ts35s1bpk"/></g><g filter="url(#iAjs5pe)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="qfni0kjsa"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="qfni0kjsa"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="qfni0kjsa"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="iJSlXzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.473 24.032)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iOoOjsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.219)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="ix6vz4b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.907)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="ilmt7Yb" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="gk62c0bvt"/><stop offset="1" class="sakdc30lg"/></radialGradient><radialGradient id="iSYNswc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="ht983-f_u"/><stop offset="1" class="wmy4ysbjz"/></radialGradient><radialGradient id="iyogxjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01636 0 0 3.52864 8.585 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iBRMQ0d" cx="0" cy="0" r="1" gradientTransform="matrix(.9499 -.69167 .78945 1.08417 21.862 12.533)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iiz4eqc" cx="0" cy="0" r="1" gradientTransform="matrix(.94364 -1.73561 1.01586 .55231 21.387 13.781)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ijemD5b" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38017 .38407 21.435 12.837)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iNFaRtd" cx="0" cy="0" r="1" gradientTransform="rotate(96.618 3.784 13.458)scale(9.24912 10.5608)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="l58-idrcp"/><stop offset=".989" class="qkuronp0z"/></radialGradient><radialGradient id="iD0xIve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50185 1.84843 0 18.655 11.376)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iuoVaIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.59812 1.9874 0 13.418 11.338)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="itw9gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44069 -5.875 0 15.62 10.844)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="o_h54ebqa"/><stop offset="1" class="rzl4j79lt"/></radialGradient><radialGradient id="icWgY0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.9487 5.08934 -8.65485 -6.71509 20.201 3.975)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="izj7nre" cx="0" cy="0" r="1" gradientTransform="matrix(-.21198 -2.2894 1.12438 -.1041 11.207 8.657)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iwWvxSV" cx="0" cy="0" r="1" gradientTransform="matrix(.98716 -2.2595 1.8428 .8051 20.816 10.841)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iTNpNje" cx="0" cy="0" r="1" gradientTransform="matrix(1.14072 1.41543 -1.24972 1.00717 15.068 2.954)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iSJoFRb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6672 -3.48798 1.20515 .57604 20.772 7.99)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iCC3Lzd" cx="0" cy="0" r="1" gradientTransform="matrix(.3086 1.16614 -1.96455 .51988 16.82 2.954)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iWwZUbl" cx="0" cy="0" r="1" gradientTransform="matrix(1.30797 1.83718 -3.85965 2.74786 10.822 4.403)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="irsPi6b" cx="0" cy="0" r="1" gradientTransform="matrix(-8.51631 3.73096 -4.58177 -10.4584 17.361 7.823)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iKD40bb" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 17.003 .475)scale(.72129 2.16389)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iCVEN6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.22791 0 18.463 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="inYkQsc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 12.076 1.618)scale(.43456 .59827)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUpDKid" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03779 -1.22797 0 13.45 12.437)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i139c4b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.617 -.306)scale(.56764 .68234)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iFFrXxB" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".25"/></filter><filter id="iCTaZue" width="4.12" height="2.78" x="13.959" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="iZbIEcc" width="3.58" height="4.539" x="12.543" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="igmmLyc" width="3.6" height="4.539" x="15.879" y="19.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="i5QOd8d" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.447059 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="iFnTVYc" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2676" result="effect2_innerShadow_4002_2676"/></filter><filter id="iQiOEkP" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2676" result="effect2_innerShadow_4002_2676"/></filter><filter id="i8dhbWd" width="3.286" height="3.286" x="8.86" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".25"/></filter><filter id="iUPdEPc" width="4.086" height="4.086" x="19.516" y="10.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="ibmDX4W" width="3.286" height="3.286" x="19.791" y="11.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".25"/></filter><filter id="i9V0dTd" width="14.89" height="9.492" x="8.554" y="2.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2676" result="effect2_innerShadow_4002_2676"/></filter><filter id="ijXBDmc" width="3.522" height="4.581" x="13.923" y="11.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".375"/></filter><filter id="iJENCRd" width="2.656" height="3.581" x="14.631" y="11.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".125"/></filter><filter id="ihhBQEb" width="2.656" height="3.581" x="14.631" y="11.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".125"/></filter><filter id="in6IDHc" width="4.097" height="1.632" x="13.911" y="15.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".05"/></filter><filter id="iVUCnpb" width=".874" height=".77" x="17.634" y="11.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".05"/></filter><filter id="iiU3gyd" width=".964" height=".99" x="18.614" y="11.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".1"/></filter><filter id="inRn0HC" width="1.074" height="1.135" x="13.51" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".1"/></filter><filter id="iuifPre" width="1.019" height=".78" x="12.628" y="11.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".05"/></filter><filter id="iBuAije" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><filter id="icZs5Ib" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".075"/></filter><filter id="ixvYg7b" width="2.624" height="2.748" x="14.643" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2676" result="effect2_innerShadow_4002_2676"/></filter><filter id="iSzcDvd" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2676" result="effect2_innerShadow_4002_2676"/></filter><filter id="iaq2A3b" width="13.899" height="3.448" x="9.147" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2676" stdDeviation=".25"/></filter><filter id="iAjs5pe" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2676"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="iySt08c" x1="13.095" x2="8.763" y1="26.864" y2="26.864" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="iyvwr9c" x1="10.504" x2="9.768" y1="13.158" y2="13.158" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="i93yzTb" x1="22.683" x2="21.742" y1="11.583" y2="14.497" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i2T8Cgd" x1="20.596" x2="11.822" y1="13.285" y2="14.592" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="ih7e9Mc" x1="9.759" x2="12.416" y1="16.383" y2="16.036" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iOU0gcb" x1="10.374" x2="13.708" y1="12.53" y2="6.607" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i2uviBb" x1="14.966" x2="16.044" y1="14.042" y2="14.042" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="imPB8Ae" x1="17.037" x2="15.859" y1="14.413" y2="14.396" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="izbencd" x1="16.183" x2="16.183" y1="15.265" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iudTiAC" x1="15.959" x2="15.959" y1="12.06" y2="14.047" gradientUnits="userSpaceOnUse"><stop class="o8oojwb7d"/><stop offset="1" class="mdrbaxbgb"/></linearGradient><linearGradient id="igXE6hb" x1="19.356" x2="18.996" y1="12.115" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBfLjNd" x1="14.304" x2="13.944" y1="12.115" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i945GOe" x1="7.318" x2="13.13" y1="7.657" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iBrxMjb" x1="16.899" x2="14.793" y1="4.542" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer" /></template>
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

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.af47qnbed {
  cx: 21.434px;
  cy: 12.837px;
  r: 1.918px;
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
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

.c7a564dhv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 11.194c.75 0 1.384.517 1.556 1.216a.315.315 0 0 1-.308.391H17.39a.264.264 0 0 1-.261-.312a1.606 1.606 0 0 1 1.575-1.295");
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.d6-8jybix {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.39 11.722c.073.098-.08.217-.254.347c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.412s.373-.155.447-.058");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dee3snbxe {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.296-5.723-11.26-12.138-11.26S4.328 23.639 3.862 29.935");
}

.dn3_eabxs {
  cx: 21.435px;
  cy: 12.837px;
  r: 1.143px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.dvm4z0-tz {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.959 16.434c-.583 0-1.13-.138-1.591-.378c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.148-.07-.32-.227-.24a3.44 3.44 0 0 1-1.592.378");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
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

.ef2daacsc {
  d: path("M18.465 11.506a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .993-1.296");
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ewagz7_9h {
  stop-color: var(--svg-color--3a84b9, #3A84B9);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f1vhuirkb {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
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

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fm89bjp3t {
  cx: 21.435px;
  cy: 12.837px;
  r: 1.143px;
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

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gk62c0bvt {
  stop-color: var(--svg-color--e7a446, #E7A446);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.ho6_1fbmc {
  cx: 10.504px;
  cy: 12.837px;
  r: 1.143px;
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.ht983-f_u {
  stop-color: var(--svg-color--d1814c, #D1814C);
}

.htxp2lohr {
  d: path("m17.577 29.934l-.927-5.202a.15.15 0 0 0-.147-.123h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i3ahy1b3f {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m21.496 5.394l.493.245c.863.43 1.612 1.349 1.427 2.39l-.934 3.555c-.06.36-.299.603-.657.612c.04-.578.079-1.512.094-1.66c.05-.497-.028-.644-.485-1.097c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.98l-.185.185c-.246.183-.37.568-.37.874c.016.179.04 1.208.067 1.636a.73.73 0 0 1-.683-.61l-.847-3.494c-.123-.98.539-1.96 1.402-2.39c1.165-.51 1.589-1.285 2.527-2.083c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.061 2.712.613l.925.92c.246.306.554.49.924.673");
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.iqbcdnbik {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.j-372xbis {
  d: path("M19.378 12.396a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
}

.j2ao_sb9l {
  d: path("M8.797 4.266c-.625.258-1.356 1.025-.969 2.375s.526 1.802.547 1.86c.04.166.223.5.633.5h.39a.46.46 0 0 0 .301-.134c.142-.134 2.254-1.596 5.827-1.718c3.645.122 6.633 1.584 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.116-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jc659fuoj {
  d: path("m21.496 5.394l.493.245c.863.43 1.612 1.349 1.427 2.39l-.934 3.555c-.06.36-.299.603-.657.612c.04-.578.079-1.512.094-1.66c.05-.497-.028-.644-.485-1.097c-.246-.245-.431-.613-.431-.98v-.981c0-.307-.247-.552-.493-.613c-.74-.184-2.28-.49-4.5-.49c-2.218 0-3.759.306-4.499.49a.6.6 0 0 0-.492.613v.98c0 .368-.124.736-.432.98l-.185.185c-.246.183-.37.568-.37.874c.016.179.04 1.208.067 1.636a.73.73 0 0 1-.683-.61l-.847-3.494c-.123-.98.539-1.96 1.402-2.39c1.165-.51 1.589-1.285 2.527-2.083c.678-.613 1.664-.797 2.527-.368a3.4 3.4 0 0 0 1.91 0c.925-.306 1.972-.061 2.712.613l.925.92c.246.306.554.49.924.673");
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.jdr9j27so {
  d: path("m15.52 12.384l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l_ou99l7k {
  d: path("M14.384 12.41c0-.331-.27-.552-.343-.619l-.33.32l.203.416z");
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lisfvhbjo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.21 11.193c-.75 0-1.385.517-1.557 1.216c-.051.2.102.392.307.392h2.564c.163 0 .293-.15.26-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.lsv-gob5y {
  cx: 13.138px;
  cy: 11.944px;
  rx: 0.448px;
  ry: 0.227px;
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mdrbaxbgb {
  stop-color: var(--svg-color--e49f2d, #E49F2D);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.nam0sg75y {
  d: path("M10.1 12.133c-.03-.36-.068-1.388-.067-1.652c0-.307.123-.674.37-.858l.184-.184c.308-.245.432-.613.432-.98v-.981c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.736.431.98c.577.405.541.627.493 1.104c-.014.148-.061 1.372-.102 1.654l-.305 4.548c-.185 2.034-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.416-3.689-3.45z");
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

.o_h54ebqa {
  stop-color: var(--svg-color--cb7b2e, #CB7B2E);
}

.o_t6_vals {
  fill: var(--svg-color--000, #000);
  d: path("M14.034 12.53a.585.585 0 0 0-.587-.586a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.o8oojwb7d {
  stop-color: var(--svg-color--e49f2d, #E49F2D);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qfni0kjsa {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.854-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.432c2.085-.862 7.432-2.032 12.945-.012a.775.775 0 1 1-.533 1.455");
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qkuronp0z {
  stop-color: var(--svg-color--db8778, #DB8778);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rb_p-obxu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.959 16.434c-.583 0-1.13-.138-1.591-.378c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.148-.07-.32-.227-.24a3.44 3.44 0 0 1-1.592.378Z");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rzl4j79lt {
  stop-color: var(--svg-color--cb7b2e, #CB7B2E);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sakdc30lg {
  stop-color: var(--svg-color--dd8f36, #DD8F36);
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.skpn_ly8l {
  fill: var(--svg-color--000, #000);
  d: path("M17.878 12.53c0-.325.26-.586.587-.586a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
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

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vnlonib2h {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.652 2.145-2.223l-2.145-.332z");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w4srnfb7y {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.079.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wmy4ysbjz {
  stop-color: var(--svg-color--d1814c, #D1814C);
  stop-opacity: 0;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
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

.y0jvqtbxh {
  d: path("m15.52 12.51l-.61 1.952a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
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

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z0wtlwbgo {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.643 12.697L14.7 14.65c-.117.401.164.803.56.803h.848c.397 0 .678-.408.56-.803l-.572-1.953c-.122-.433-.325-.433-.453 0");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
