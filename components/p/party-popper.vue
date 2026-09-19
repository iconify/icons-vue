<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igJQmNb)"><path fill="url(#iCD7Ule)" class="ywg7rqb3s"/></g><path fill="url(#ifD9vXb)" class="ywg7rqb3s"/><path fill="url(#imDCVZc)" class="ywg7rqb3s"/><path fill="url(#iwlr4pe)" class="ywg7rqb3s"/><g filter="url(#idFBWPc)"><ellipse fill="url(#iw3X9md)" transform="rotate(39.746 12.298 18.624)" class="cusxahb2c"/></g><g filter="url(#iKEr83b)"><ellipse fill="url(#iJyHdee)" transform="rotate(39.746 12.555 18.187)" class="mhlg3lbzz"/><ellipse fill="url(#iQrX49d)" transform="rotate(39.746 12.555 18.187)" class="mhlg3lbzz"/><ellipse fill="url(#i8qRCLc)" transform="rotate(39.746 12.555 18.187)" class="mhlg3lbzz"/></g><circle fill="url(#iSiFoWo)" class="beqzus4yv"/><circle fill="url(#iHHnLne)" class="beqzus4yv"/><circle fill="url(#iRNWngs)" class="gszgpbb5e"/><circle fill="url(#iG7uaSc)" class="gszgpbb5e"/><circle fill="url(#igqokDd)" class="gszgpbb5e"/><circle fill="url(#i3fmPve)" class="gna6rbcmn"/><circle fill="url(#ivMlCAd)" class="gna6rbcmn"/><circle fill="url(#iyyKFSc)" class="xwirf-b9l"/><circle fill="url(#iy4f1Sw)" class="xwirf-b9l"/><circle fill="url(#iqNriNF)" class="xwirf-b9l"/><circle fill="url(#iM4GJAd)" class="rm2_irx4n"/><circle fill="url(#igr9R6b)" class="rm2_irx4n"/><path fill="url(#iElBtZC)" class="grr8r2b-m"/><path fill="url(#iMUweec)" class="a4qwg3bbj"/><g filter="url(#ioRQg6b)"><path fill="url(#idDuwBN)" clip-rule="evenodd" class="ti5klwb_l"/><path fill="url(#iOaU64Z)" clip-rule="evenodd" class="ti5klwb_l"/></g><path fill="url(#icmzhPe)" clip-rule="evenodd" class="mg8ehhbwk"/><path fill="url(#iXHMqIe)" clip-rule="evenodd" class="mg8ehhbwk"/><path fill="url(#iGpl25c)" clip-rule="evenodd" class="mg8ehhbwk"/><path fill="url(#iiPJLGR)" clip-rule="evenodd" class="mg8ehhbwk"/><path fill="url(#ifQ0f4b)" clip-rule="evenodd" class="tcfbjcc0e"/><path fill="url(#iQoQaFc)" clip-rule="evenodd" class="tcfbjcc0e"/><path fill="url(#iv6T02c)" clip-rule="evenodd" class="tcfbjcc0e"/><path fill="url(#i8cosjc)" clip-rule="evenodd" class="tcfbjcc0e"/><g filter="url(#ixGYXJH)"><path fill="url(#iYFDG5c)" clip-rule="evenodd" class="xqooysf-n"/><path fill="url(#iZ9bRVy)" clip-rule="evenodd" class="xqooysf-n"/></g><path fill="url(#iLhEufd)" class="uyciboble"/><path fill="url(#iXdb8ad)" class="uyciboble"/><g filter="url(#iSBoB8b)"><path class="ia_bpacvu"/></g><path fill="url(#igmmxxc)" class="j92c1ifws"/><g filter="url(#iPUZ6es)"><path stroke="url(#i8yR0pc)" class="s175ahb8f"/></g><g filter="url(#iVvItxs)"><path stroke="url(#ilT60bd)" class="lcwqyzb-u"/></g><defs><radialGradient id="iQrX49d" cx="0" cy="0" r="1" gradientTransform="rotate(-109.125 11.529 7.252)scale(6.4775 1.81427)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="p4hlzcb-j"/><stop offset="1" class="vxtltwb3v"/></radialGradient><radialGradient id="i8qRCLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89264 -6.22832 3.64737 1.10835 15.236 20.612)" gradientUnits="userSpaceOnUse"><stop class="lo63_mbqo"/><stop offset="1" class="fqz3gta8w"/></radialGradient><radialGradient id="iSiFoWo" cx="0" cy="0" r="1" gradientTransform="rotate(138.668 4.788 10.757)scale(1.72711)" gradientUnits="userSpaceOnUse"><stop class="bytoh5baj"/><stop offset="1" class="el66_cb2b"/></radialGradient><radialGradient id="iHHnLne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63032 .59175 -.64863 -1.78704 15.193 15.834)" gradientUnits="userSpaceOnUse"><stop offset=".535" class="lr7mo2baq"/><stop offset="1" class="nd-w3_2uc"/></radialGradient><radialGradient id="iRNWngs" cx="0" cy="0" r="1" gradientTransform="rotate(134.569 8.076 16.542)scale(1.97753)" gradientUnits="userSpaceOnUse"><stop class="hmr6mubjl"/><stop offset="1" class="sfwqfye9j"/></radialGradient><radialGradient id="iG7uaSc" cx="0" cy="0" r="1" gradientTransform="rotate(100.827 3.31 21.505)scale(1.95883)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="f0a64x7yk"/><stop offset=".964" class="genyixblf"/></radialGradient><radialGradient id="igqokDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67412 -1.06415 1.25319 -1.9715 25.405 23.105)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="r68noib4b"/><stop offset=".907" class="z_s_xn33m"/></radialGradient><radialGradient id="i3fmPve" cx="0" cy="0" r="1" gradientTransform="rotate(132.387 10.898 8.719)scale(2.06012)" gradientUnits="userSpaceOnUse"><stop class="z2qrc69sz"/><stop offset="1" class="cfjpedcqf"/></radialGradient><radialGradient id="ivMlCAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.21876 .29276 -2.48843 24.331 7.234)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="fvqlibb0g"/><stop offset="1" class="ylemfpb8z"/></radialGradient><radialGradient id="iyyKFSc" cx="0" cy="0" r="1" gradientTransform="rotate(139.574 4.858 3.427)scale(1.84118)" gradientUnits="userSpaceOnUse"><stop class="sgcdhebfk"/><stop offset="1" class="u5u7wbb1y"/></radialGradient><radialGradient id="iy4f1Sw" cx="0" cy="0" r="1" gradientTransform="rotate(-178.519 5.278 1.518)scale(1.91464 1.82297)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="az_outbtd"/><stop offset=".944" class="s61ykx04a"/></radialGradient><radialGradient id="iqNriNF" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2 -2 -.4375 10.3 2.688)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="m6w3ayb1w"/><stop offset="1" class="s3mkrhbkz"/></radialGradient><radialGradient id="iM4GJAd" cx="0" cy="0" r="1" gradientTransform="rotate(132.387 1.21 5.098)scale(2.06012)" gradientUnits="userSpaceOnUse"><stop class="z2qrc69sz"/><stop offset="1" class="cfjpedcqf"/></radialGradient><radialGradient id="igr9R6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.21876 .29276 -2.48843 5.436 8.328)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="fvqlibb0g"/><stop offset="1" class="ylemfpb8z"/></radialGradient><radialGradient id="iElBtZC" cx="0" cy="0" r="1" gradientTransform="matrix(-2.90624 3.09375 -6.77356 -6.36302 11.222 25.078)" gradientUnits="userSpaceOnUse"><stop class="kjo_7158j"/><stop offset="1" class="gurd4v4-b"/></radialGradient><radialGradient id="iMUweec" cx="0" cy="0" r="1" gradientTransform="rotate(131.598 -2.591 15.673)scale(2.62017 6.62793)" gradientUnits="userSpaceOnUse"><stop class="kjo_7158j"/><stop offset="1" class="gurd4v4-b"/></radialGradient><radialGradient id="idDuwBN" cx="0" cy="0" r="1" gradientTransform="rotate(168.283 13.157 7.358)scale(4.30854 1.60742)" gradientUnits="userSpaceOnUse"><stop class="y6en7ey_m"/><stop offset="1" class="haw9z4buo"/></radialGradient><radialGradient id="iOaU64Z" cx="0" cy="0" r="1" gradientTransform="rotate(-127.355 16 1.624)scale(4.44241 7.91727)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="txd0uebos"/><stop offset="1" class="p7g31pbfb"/></radialGradient><radialGradient id="iXHMqIe" cx="0" cy="0" r="1" gradientTransform="rotate(128.217 7.687 7.173)scale(7.76064 4.747)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="jz1zg45ey"/><stop offset=".951" class="e8qpqfbrs"/></radialGradient><radialGradient id="iGpl25c" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 .23438 -.78682 3.6718 17.69 4.672)" gradientUnits="userSpaceOnUse"><stop class="d_w15mbdh"/><stop offset="1" class="p8-4wbcjz"/></radialGradient><radialGradient id="iiPJLGR" cx="0" cy="0" r="1" gradientTransform="rotate(141.953 9.567 4.557)scale(1.36904 1.23086)" gradientUnits="userSpaceOnUse"><stop class="kom8yic-g"/><stop offset="1" class="g-arl9bqn"/></radialGradient><radialGradient id="iQoQaFc" cx="0" cy="0" r="1" gradientTransform="rotate(-129.838 15.295 7.401)scale(7.98002 20.0036)" gradientUnits="userSpaceOnUse"><stop offset=".623" class="ggknfrxcf"/><stop offset=".962" class="f4j-qmbit"/></radialGradient><radialGradient id="iv6T02c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2101 2.73113 -5.49097 -.42241 23.892 19.58)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="nzf8op1qa"/><stop offset="1" class="kglr322gg"/></radialGradient><radialGradient id="i8cosjc" cx="0" cy="0" r="1" gradientTransform="matrix(.27136 -.7003 .55226 .214 27.954 17.279)" gradientUnits="userSpaceOnUse"><stop class="q2t_9h49d"/><stop offset="1" class="nrpzf7aii"/></radialGradient><radialGradient id="iYFDG5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1971 7.21318 -2.70234 -.44848 10.844 6.436)" gradientUnits="userSpaceOnUse"><stop class="rzuu_n9vd"/><stop offset="1" class="iw6u2ss3y"/></radialGradient><radialGradient id="iZ9bRVy" cx="0" cy="0" r="1" gradientTransform="rotate(31.176 -21.536 19.58)scale(4.80845 15.0903)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="qasdf56az"/><stop offset="1" class="j8-cghb3m"/></radialGradient><radialGradient id="iLhEufd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.23 11 -.054)scale(2.73834 2.04693)" gradientUnits="userSpaceOnUse"><stop class="osncfbr7r"/><stop offset="1" class="ogdpgybju"/></radialGradient><radialGradient id="iXdb8ad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13335 -1.46866 .59503 -.45918 17.31 7.453)" gradientUnits="userSpaceOnUse"><stop class="gd675f-sn"/><stop offset="1" class="p5ufqmbxd"/></radialGradient><radialGradient id="igmmxxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 2.57813 -1.43484 -.12175 18.144 9.485)" gradientUnits="userSpaceOnUse"><stop class="vr-9v2bxe"/><stop offset="1" class="kigy7rbry"/></radialGradient><linearGradient id="iCD7Ule" x1="4.222" x2="12.284" y1="19.984" y2="26.984" gradientUnits="userSpaceOnUse"><stop class="g3cup3o0h"/><stop offset="1" class="rj919fb9t"/></linearGradient><linearGradient id="ifD9vXb" x1="3.331" x2="5.69" y1="21.068" y2="21.547" gradientUnits="userSpaceOnUse"><stop class="zkz5nr3-p"/><stop offset="1" class="dvc2a4n7g"/></linearGradient><linearGradient id="imDCVZc" x1="19.736" x2="15.753" y1="23.828" y2="24.484" gradientUnits="userSpaceOnUse"><stop class="s00nmsbyr"/><stop offset="1" class="hr9lu7bpa"/></linearGradient><linearGradient id="iwlr4pe" x1="11.155" x2="8.597" y1="12.391" y2="16.734" gradientUnits="userSpaceOnUse"><stop class="f6-nlw04w"/><stop offset="1" class="o46ju-b_r"/></linearGradient><linearGradient id="iw3X9md" x1="12.323" x2="13.352" y1="21.804" y2="14.923" gradientUnits="userSpaceOnUse"><stop class="qkrkhyb8e"/><stop offset="1" class="h8-oixlet"/></linearGradient><linearGradient id="iJyHdee" x1="5.147" x2="21.627" y1="17.865" y2="18.67" gradientUnits="userSpaceOnUse"><stop class="pxasrvkyp"/><stop offset="1" class="lu54k2bbt"/></linearGradient><linearGradient id="icmzhPe" x1="19.062" x2="14.58" y1="2.081" y2="12.823" gradientUnits="userSpaceOnUse"><stop class="csmwpn-ck"/><stop offset="1" class="wcx2bx1xk"/></linearGradient><linearGradient id="ifQ0f4b" x1="14.45" x2="27.86" y1="21.695" y2="18.181" gradientUnits="userSpaceOnUse"><stop class="wy0h59b9h"/><stop offset="1" class="y7_vkhbej"/></linearGradient><linearGradient id="i8yR0pc" x1="13.597" x2="16.378" y1="8.189" y2="7.508" gradientUnits="userSpaceOnUse"><stop class="q9l4tbjtj"/><stop offset="1" class="injk5jbpl"/></linearGradient><linearGradient id="ilT60bd" x1="19.253" x2="15.347" y1="1.953" y2="10.953" gradientUnits="userSpaceOnUse"><stop class="nnl1f6_nv"/><stop offset="1" class="dui_jqbpr"/></linearGradient><filter id="igJQmNb" width="17.162" height="18.284" x="2.574" y="11.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_504"/></filter><filter id="idFBWPc" width="15.203" height="13.421" x="4.697" y="11.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_504" stdDeviation=".25"/></filter><filter id="iKEr83b" width="13.45" height="11.725" x="5.83" y="12.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_504" stdDeviation=".1"/></filter><filter id="ioRQg6b" width="9.725" height="4.549" x="19.679" y="10.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.270588 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_504"/></filter><filter id="ixGYXJH" width="4.31" height="13.369" x="7.567" y="6.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.184314 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_504"/></filter><filter id="iSBoB8b" width="2.512" height="3.858" x="16.342" y="9.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.439216 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_504"/></filter><filter id="iPUZ6es" width="3.55" height="2.822" x="13.45" y="7.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_504" stdDeviation=".15"/></filter><filter id="iVvItxs" width="3.888" height="8.45" x="16.184" y="2.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_504" stdDeviation=".225"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:party-popper" /></template>
<style>
.a4qwg3bbj {
  d: path("M10.457 28.163c-1.253.07-2.946-.952-4.704-2.413c-1.5-1.297-2.24-2.706-2.396-3.466l-.496 2.857c.122.483.497 1.14 1.58 2.25c1.21 1.24 2.428 1.724 3.15 1.861l1.532-.582z");
}

.az_outbtd {
  stop-color: var(--svg-color--aa904b, #AA904B);
  stop-opacity: 0;
}

.beqzus4yv {
  cx: 14.956px;
  cy: 16px;
  r: 1.203px;
}

.bytoh5baj {
  stop-color: var(--svg-color--5ac0ff, #5AC0FF);
}

.cfjpedcqf {
  stop-color: var(--svg-color--e3189d, #E3189D);
}

.csmwpn-ck {
  stop-color: var(--svg-color--20b2ee, #20B2EE);
}

.cusxahb2c {
  cx: 12.298px;
  cy: 18.624px;
  rx: 8.772px;
  ry: 3.464px;
}

.d_w15mbdh {
  stop-color: var(--svg-color--4d8ec0, #4D8EC0);
}

.dui_jqbpr {
  stop-color: var(--svg-color--5bddff, #5BDDFF);
  stop-opacity: 0;
}

.dvc2a4n7g {
  stop-color: var(--svg-color--b1853b, #B1853B);
  stop-opacity: 0;
}

.e8qpqfbrs {
  stop-color: var(--svg-color--4274d2, #4274D2);
}

.el66_cb2b {
  stop-color: var(--svg-color--3279b6, #3279B6);
}

.f0a64x7yk {
  stop-color: var(--svg-color--e76260, #E76260);
  stop-opacity: 0;
}

.f4j-qmbit {
  stop-color: var(--svg-color--526579, #526579);
}

.f6-nlw04w {
  stop-color: var(--svg-color--e6bf69, #E6BF69);
}

.fqz3gta8w {
  stop-color: var(--svg-color--bc7f28, #BC7F28);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvqlibb0g {
  stop-color: var(--svg-color--b63173, #B63173);
  stop-opacity: 0;
}

.g-arl9bqn {
  stop-color: var(--svg-color--5adeff, #5ADEFF);
  stop-opacity: 0;
}

.g3cup3o0h {
  stop-color: var(--svg-color--b3843c, #B3843C);
}

.gd675f-sn {
  stop-color: var(--svg-color--49a4d4, #49A4D4);
}

.genyixblf {
  stop-color: var(--svg-color--e76260, #E76260);
}

.ggknfrxcf {
  stop-color: var(--svg-color--526579, #526579);
  stop-opacity: 0;
}

.gna6rbcmn {
  cx: 23.823px;
  cy: 7.016px;
  r: 1.203px;
}

.grr8r2b-m {
  d: path("M15.953 26.01c-2.606-.182-4.434-.962-7.395-3.408c-2.548-2.105-3.813-3.972-4.235-5.876l-.489 2.813c.2 1.102 1.06 2.64 2.763 4.18c2.227 2.013 4.445 3.437 6.638 3.375a182 182 0 0 0 2.718-1.085");
}

.gszgpbb5e {
  cx: 24.831px;
  cy: 22.906px;
  r: 1.203px;
}

.gurd4v4-b {
  stop-color: var(--svg-color--356db9, #356DB9);
}

.h8-oixlet {
  stop-color: var(--svg-color--f5bd55, #F5BD55);
}

.haw9z4buo {
  stop-color: var(--svg-color--f422a7, #F422A7);
}

.hmr6mubjl {
  stop-color: var(--svg-color--fdd46c, #FDD46C);
}

.hr9lu7bpa {
  stop-color: var(--svg-color--f9c26c, #F9C26C);
  stop-opacity: 0;
}

.ia_bpacvu {
  fill: var(--svg-color--44b6ff, #44B6FF);
  d: path("M18.242 9.568c.15.796.154 1.736-.011 2.803a.95.95 0 1 1-1.878-.29q.055-.357.08-.67c.982-.617 1.63-1.437 1.809-1.843");
}

.injk5jbpl {
  stop-color: var(--svg-color--4eaff2, #4EAFF2);
  stop-opacity: 0;
}

.iw6u2ss3y {
  stop-color: var(--svg-color--fd2f89, #FD2F89);
}

.j8-cghb3m {
  stop-color: var(--svg-color--db2c6e, #DB2C6E);
}

.j92c1ifws {
  d: path("M18.242 9.568c.15.796.154 1.736-.011 2.803a.95.95 0 1 1-1.878-.29q.055-.357.08-.67c.982-.617 1.63-1.437 1.809-1.843");
}

.jz1zg45ey {
  stop-color: var(--svg-color--4274d2, #4274D2);
  stop-opacity: 0;
}

.kglr322gg {
  stop-color: var(--svg-color--6972ff, #6972FF);
  stop-opacity: 0;
}

.kigy7rbry {
  stop-color: var(--svg-color--4ab5f8, #4AB5F8);
  stop-opacity: 0;
}

.kjo_7158j {
  stop-color: var(--svg-color--3365ff, #3365FF);
}

.kom8yic-g {
  stop-color: var(--svg-color--5adeff, #5ADEFF);
}

.lcwqyzb-u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.472 3.016c-.084 1.51-.738 5.075-2.688 7.25");
}

.lo63_mbqo {
  stop-color: var(--svg-color--bc7f28, #BC7F28);
}

.lr7mo2baq {
  stop-color: var(--svg-color--3a619e, #3A619E);
  stop-opacity: 0;
}

.lu54k2bbt {
  stop-color: var(--svg-color--b57f1e, #B57F1E);
}

.m6w3ayb1w {
  stop-color: var(--svg-color--c47072, #C47072);
  stop-opacity: 0;
}

.mg8ehhbwk {
  fill-rule: evenodd;
  d: path("M19.104 2.082a.95.95 0 0 1 .905.994a18 18 0 0 1-.479 3.207c-.262 1.074-.665 2.264-1.286 3.285c.15.796.154 1.735-.011 2.803a.95.95 0 0 1-1.878-.29q.055-.357.08-.672a3 3 0 0 1-.566.226a2.44 2.44 0 0 1-2.04-.312c-1.074-.715-1.569-2.28-.738-3.56c.79-1.216 2.438-1.547 3.69-.681q.217.15.407.337c.2-.505.364-1.045.496-1.586c.281-1.152.398-2.232.427-2.846a.95.95 0 0 1 .993-.905m-2.947 7.14c-.144-.3-.316-.48-.456-.577c-.392-.271-.822-.145-1.017.154a.694.694 0 0 0 .198.943c.12.08.273.12.476.063c.184-.052.465-.2.799-.582");
}

.mhlg3lbzz {
  cx: 12.555px;
  cy: 18.187px;
  rx: 8.13px;
  ry: 2.915px;
}

.nd-w3_2uc {
  stop-color: var(--svg-color--3a619e, #3A619E);
}

.nnl1f6_nv {
  stop-color: var(--svg-color--5bddff, #5BDDFF);
}

.nrpzf7aii {
  stop-color: var(--svg-color--55bfff, #55BFFF);
  stop-opacity: 0;
}

.nzf8op1qa {
  stop-color: var(--svg-color--6972ff, #6972FF);
}

.o46ju-b_r {
  stop-color: var(--svg-color--e6bf69, #E6BF69);
  stop-opacity: 0;
}

.ogdpgybju {
  stop-color: var(--svg-color--336baf, #336BAF);
  stop-opacity: 0;
}

.osncfbr7r {
  stop-color: var(--svg-color--336baf, #336BAF);
}

.p4hlzcb-j {
  stop-color: var(--svg-color--ca851e, #CA851E);
}

.p5ufqmbxd {
  stop-color: var(--svg-color--49a4d4, #49A4D4);
  stop-opacity: 0;
}

.p7g31pbfb {
  stop-color: var(--svg-color--b8306f, #B8306F);
}

.p8-4wbcjz {
  stop-color: var(--svg-color--4d8ec0, #4D8EC0);
  stop-opacity: 0;
}

.pxasrvkyp {
  stop-color: var(--svg-color--f3ab2c, #F3AB2C);
}

.q2t_9h49d {
  stop-color: var(--svg-color--55bfff, #55BFFF);
}

.q9l4tbjtj {
  stop-color: var(--svg-color--4eaff2, #4EAFF2);
}

.qasdf56az {
  stop-color: var(--svg-color--db2c6e, #DB2C6E);
  stop-opacity: 0;
}

.qkrkhyb8e {
  stop-color: var(--svg-color--fccb57, #FCCB57);
}

.r68noib4b {
  stop-color: var(--svg-color--aa885a, #AA885A);
  stop-opacity: 0;
}

.rj919fb9t {
  stop-color: var(--svg-color--f17a61, #F17A61);
}

.rm2_irx4n {
  cx: 4.928px;
  cy: 8.109px;
  r: 1.203px;
}

.rzuu_n9vd {
  stop-color: var(--svg-color--ff3aaa, #FF3AAA);
}

.s00nmsbyr {
  stop-color: var(--svg-color--f9c26c, #F9C26C);
}

.s175ahb8f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.55 8.172c-.266-.36-1.118-1-2.188-.336c-.359.223-.57 1.062-.406 1.633");
}

.s3mkrhbkz {
  stop-color: var(--svg-color--c47072, #C47072);
}

.s61ykx04a {
  stop-color: var(--svg-color--aa904b, #AA904B);
}

.sfwqfye9j {
  stop-color: var(--svg-color--f09c53, #F09C53);
}

.sgcdhebfk {
  stop-color: var(--svg-color--fff46f, #FFF46F);
}

.tcfbjcc0e {
  fill-rule: evenodd;
  d: path("M13.842 22.606a19.5 19.5 0 0 1-2.115-1.365c1.086-1.347 3.027-3.113 5.557-4.388c4.157-2.096 8.741-.959 10.61-.218a1.25 1.25 0 1 1-.922 2.324c-1.601-.635-5.345-1.496-8.563.126c-2.122 1.07-3.7 2.508-4.567 3.521");
}

.ti5klwb_l {
  fill-rule: evenodd;
  d: path("M27.903 13.109c-3.598-.703-5.724.945-6.398 1.684a1.05 1.05 0 1 1-1.552-1.414c1.045-1.147 3.873-3.207 8.353-2.331a1.05 1.05 0 0 1-.403 2.06");
}

.txd0uebos {
  stop-color: var(--svg-color--b8306f, #B8306F);
  stop-opacity: 0;
}

.u5u7wbb1y {
  stop-color: var(--svg-color--efb93c, #EFB93C);
}

.uyciboble {
  d: path("M12.855 8.212q.092-.228.234-.448c.79-1.217 2.438-1.548 3.69-.682q.217.15.407.337q.06-.155.118-.314l.005.02c-.257.81-.834 1.678-1.155 2.096c-.144-.3-.315-.48-.455-.576c-.392-.271-.823-.145-1.017.154l-.021.035z");
}

.vr-9v2bxe {
  stop-color: var(--svg-color--4ab5f8, #4AB5F8);
}

.vxtltwb3v {
  stop-color: var(--svg-color--ca851e, #CA851E);
  stop-opacity: 0;
}

.wcx2bx1xk {
  stop-color: var(--svg-color--2689da, #2689DA);
}

.wy0h59b9h {
  stop-color: var(--svg-color--3797e2, #3797E2);
}

.xqooysf-n {
  fill-rule: evenodd;
  d: path("M10.192 6.653A1.25 1.25 0 1 0 8.007 7.87c.507.91 1.131 2.197 1.211 3.853c.07 1.443-.27 3.273-1.651 5.469a18 18 0 0 0 1.715 1.939c1.948-2.833 2.537-5.371 2.433-7.529c-.107-2.23-.952-3.921-1.523-4.948");
}

.xwirf-b9l {
  cx: 9.991px;
  cy: 3.367px;
  r: 1.203px;
}

.y6en7ey_m {
  stop-color: var(--svg-color--ff3ba9, #FF3BA9);
}

.y7_vkhbej {
  stop-color: var(--svg-color--37aeff, #37AEFF);
}

.ylemfpb8z {
  stop-color: var(--svg-color--b63173, #B63173);
}

.ywg7rqb3s {
  d: path("M18.687 24.856c.439-.192.621-.472.753-.637c1.186-1.48-1.343-5.875-4.954-8.418c-3.827-3.332-8.04-4.468-9.226-2.987c-.203.254-.363.6-.429.99L2.581 26.75c-.078 1.578.525 2.178.827 2.47c.547.532 1.61.983 2.72.593c4.281-1.649 8.292-3.097 12.558-4.957");
}

.z_s_xn33m {
  stop-color: var(--svg-color--aa885a, #AA885A);
}

.z2qrc69sz {
  stop-color: var(--svg-color--ff46aa, #FF46AA);
}

.zkz5nr3-p {
  stop-color: var(--svg-color--b1853b, #B1853B);
}

</style>
