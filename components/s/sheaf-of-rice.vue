<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQceq7A)" class="idjszkboa"/><path fill="url(#i94rxTb)" class="idjszkboa"/><path fill="url(#iB7d1Uc)" class="idjszkboa"/><path fill="url(#iET2gBe)" class="idjszkboa"/><path fill="url(#iHKu8Ec)" class="fq_0a2bjg"/><path fill="url(#i1laBFb)" class="fq_0a2bjg"/><path fill="url(#ifR8SSb)" class="fq_0a2bjg"/><path fill="url(#iLzSUqe)" class="fq_0a2bjg"/><path fill="url(#ixZ0Yyb)" class="pz-gs_6iq"/><path fill="url(#iZTC3Ge)" class="pz-gs_6iq"/><path fill="url(#i8oVGVd)" class="mgfda9-yg"/><path fill="url(#iFH1L7d)" class="mgfda9-yg"/><g filter="url(#iEMAxhD)"><path stroke="url(#i1WI1uc)" class="g-9g2nwtn"/></g><g filter="url(#iPmbUUc)"><path stroke="url(#ivD1aTc)" class="jjsf3-17u"/></g><g filter="url(#itPhFHd)"><path fill="url(#iZhpmDb)" class="xyshjxbgl"/></g><path fill="url(#inyZrEb)" class="xyshjxbgl"/><path fill="url(#ipuIrBe)" class="xyshjxbgl"/><path fill="url(#imcpEFc)" class="xyshjxbgl"/><g filter="url(#iVv255m)"><path fill="url(#iPkwVBb)" class="quxsmxa9j"/></g><path fill="url(#i8rp2xc)" class="quxsmxa9j"/><path fill="url(#i13uEgG)" class="quxsmxa9j"/><g filter="url(#i88e2Qd)"><path class="n_ml7lbfi"/><path fill="url(#icwz41g)" class="etqgr4-5n"/><path fill="url(#ijH6Cge)" class="etqgr4-5n"/><path fill="url(#imSxPLd)" class="etqgr4-5n"/></g><path fill="url(#iCLwfle)" class="etqgr4-5n"/><path fill="url(#ircCYBt)" class="etqgr4-5n"/><path fill="url(#i037KZc)" class="etqgr4-5n"/><path fill="url(#i46BlfV)" class="etqgr4-5n"/><path fill="url(#ibyg9tM)" class="etqgr4-5n"/><path fill="url(#iMb7KId)" class="etqgr4-5n"/><path fill="url(#iT1Bt5b)" class="etqgr4-5n"/><g filter="url(#i9TdThe)"><path class="vfd6kab6u"/><path fill="url(#ittBXyu)" class="n4paw5bmo"/><path fill="url(#iLkWaKb)" class="n4paw5bmo"/><path fill="url(#iy3X0xc)" class="n4paw5bmo"/></g><path fill="url(#iuTiV9b)" class="n4paw5bmo"/><path fill="url(#ibifpnd)" class="n4paw5bmo"/><path fill="url(#iOKK71d)" class="n4paw5bmo"/><path fill="url(#iGpsVRd)" class="n4paw5bmo"/><path fill="url(#iG3ylKb)" class="n4paw5bmo"/><path fill="url(#iFnSpqb)" class="n4paw5bmo"/><g filter="url(#ivVX5wc)"><path stroke="url(#iIADFde)" class="d-gt9ofmd"/></g><g filter="url(#iZUy8wb)"><path stroke="url(#iF8wpne)" class="gpn27h98q"/></g><g filter="url(#ieIEM8b)"><path class="qmt6r0bac"/></g><g filter="url(#iZEUl4v)"><path class="q-ccmfbvo"/></g><defs><radialGradient id="iB7d1Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18966 0 0 -.52548 19.08 30)" gradientUnits="userSpaceOnUse"><stop class="tibx-_m4a"/><stop offset="1" class="b45q3nbyi"/></radialGradient><radialGradient id="iET2gBe" cx="0" cy="0" r="1" gradientTransform="matrix(2.2462 0 0 .19095 16.707 29.387)" gradientUnits="userSpaceOnUse"><stop class="smw1tskmy"/><stop offset="1" class="o-yxeybvr"/></radialGradient><radialGradient id="ifR8SSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85937 0 0 -.52548 13.031 25.98)" gradientUnits="userSpaceOnUse"><stop class="tibx-_m4a"/><stop offset="1" class="b45q3nbyi"/></radialGradient><radialGradient id="iLzSUqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 0 0 .17078 11.015 25.367)" gradientUnits="userSpaceOnUse"><stop class="smw1tskmy"/><stop offset="1" class="o-yxeybvr"/></radialGradient><radialGradient id="inyZrEb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 6.375 -5.2949 2.54363 18.156 23.375)" gradientUnits="userSpaceOnUse"><stop offset=".842" class="decz6kb8p"/><stop offset="1" class="l14zb5baa"/></radialGradient><radialGradient id="imcpEFc" cx="0" cy="0" r="1" gradientTransform="rotate(112.751 5.271 17.793)scale(4.20193 4.13772)" gradientUnits="userSpaceOnUse"><stop class="q60xm5poj"/><stop offset="1" class="wgngpd2bw"/></radialGradient><radialGradient id="i8rp2xc" cx="0" cy="0" r="1" gradientTransform="rotate(112.502 1.35 10.733)scale(7.2724 7.3364)" gradientUnits="userSpaceOnUse"><stop class="fyw8sxy3j"/><stop offset="1" class="d0dv-l24n"/></radialGradient><radialGradient id="i13uEgG" cx="0" cy="0" r="1" gradientTransform="matrix(-4.66876 8.47212 -8.20393 -4.52097 14.08 17.61)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="otul22bbw"/><stop offset="1" class="lpfrhb-er"/></radialGradient><radialGradient id="ijH6Cge" cx="0" cy="0" r="1" gradientTransform="matrix(2.48055 0 0 2.77254 15.408 17.163)" gradientUnits="userSpaceOnUse"><stop class="b46sikbeh"/><stop offset="1" class="dwuc60e4g"/></radialGradient><radialGradient id="iCLwfle" cx="0" cy="0" r="1" gradientTransform="matrix(9.43751 -3.8125 3.20543 7.93474 11.437 21.375)" gradientUnits="userSpaceOnUse"><stop class="cmmzqiolf"/><stop offset="1" class="gp_6pv_mk"/></radialGradient><radialGradient id="ircCYBt" cx="0" cy="0" r="1" gradientTransform="matrix(-.98352 .5 -.42513 -.83624 25 11.469)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="i037KZc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10818 .45312 -.38532 -.94236 24.11 14.188)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="i46BlfV" cx="0" cy="0" r="1" gradientTransform="rotate(154.235 9.155 11.129)scale(.97054 .82523)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="ibyg9tM" cx="0" cy="0" r="1" gradientTransform="rotate(159.827 7.865 9.862)scale(.90623 .88766)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iMb7KId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01453 .17187 -.16838 -.99395 19.397 13.438)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iLkWaKb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48323 0 0 2.77254 12.397 8.163)" gradientUnits="userSpaceOnUse"><stop class="b46sikbeh"/><stop offset="1" class="dwuc60e4g"/></radialGradient><radialGradient id="iuTiV9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.98458 .5 -.42486 -.83661 22 2.469)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="ibifpnd" cx="0" cy="0" r="1" gradientTransform="rotate(157.782 10.045 4.666)scale(1.19835 1.01824)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iOKK71d" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .42188 -.35847 -.7435 19.234 8.172)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iGpsVRd" cx="0" cy="0" r="1" gradientTransform="rotate(159.848 7.162 5.093)scale(.90709 .88778)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iG3ylKb" cx="0" cy="0" r="1" gradientTransform="rotate(170.395 8.009 2.907)scale(1.03007 1.00814)" gradientUnits="userSpaceOnUse"><stop class="lti6v5gtk"/><stop offset="1" class="guf1291_d"/></radialGradient><radialGradient id="iIADFde" cx="0" cy="0" r="1" gradientTransform="rotate(135.578 1.89 9.77)scale(1.20456 1.96882)" gradientUnits="userSpaceOnUse"><stop class="bizo-8b8u"/><stop offset="1" class="c9j967vxb"/></radialGradient><linearGradient id="iQceq7A" x1="17.133" x2="19.375" y1="29.283" y2="29.283" gradientUnits="userSpaceOnUse"><stop class="yzpr0ninf"/><stop offset="1" class="gd6vn0axr"/></linearGradient><linearGradient id="i94rxTb" x1="17.737" x2="17.737" y1="30" y2="29.492" gradientUnits="userSpaceOnUse"><stop class="hz9eqsbio"/><stop offset="1" class="tq-h-bbvk"/></linearGradient><linearGradient id="iHKu8Ec" x1="11.377" x2="13.359" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop class="yzpr0ninf"/><stop offset="1" class="gd6vn0axr"/></linearGradient><linearGradient id="i1laBFb" x1="11.89" x2="11.89" y1="25.98" y2="25.472" gradientUnits="userSpaceOnUse"><stop class="hz9eqsbio"/><stop offset="1" class="tq-h-bbvk"/></linearGradient><linearGradient id="ixZ0Yyb" x1="17.349" x2="17.349" y1="20.135" y2="30" gradientUnits="userSpaceOnUse"><stop class="qgtesx2ew"/><stop offset="1" class="bykke4mhe"/></linearGradient><linearGradient id="iZTC3Ge" x1="15.79" x2="16.338" y1="20.461" y2="20.503" gradientUnits="userSpaceOnUse"><stop class="nvrb7d_wj"/><stop offset="1" class="b6-y9swko"/></linearGradient><linearGradient id="i8oVGVd" x1="14.349" x2="14.349" y1="16.611" y2="30" gradientUnits="userSpaceOnUse"><stop class="qgtesx2ew"/><stop offset="1" class="bykke4mhe"/></linearGradient><linearGradient id="iFH1L7d" x1="12.79" x2="13.34" y1="17.055" y2="17.085" gradientUnits="userSpaceOnUse"><stop class="nvrb7d_wj"/><stop offset="1" class="b6-y9swko"/></linearGradient><linearGradient id="i1WI1uc" x1="14.115" x2="14.115" y1="12.576" y2="29.573" gradientUnits="userSpaceOnUse"><stop class="zduypibhf"/><stop offset="1" class="qmg-a-caa"/></linearGradient><linearGradient id="ivD1aTc" x1="17.078" x2="17.078" y1="21.141" y2="30.522" gradientUnits="userSpaceOnUse"><stop class="zduypibhf"/><stop offset="1" class="qmg-a-caa"/></linearGradient><linearGradient id="iZhpmDb" x1="21.034" x2="21.034" y1="20.887" y2="29.727" gradientUnits="userSpaceOnUse"><stop class="f6it9ppwy"/><stop offset="1" class="q2gb_ds8v"/></linearGradient><linearGradient id="ipuIrBe" x1="18.437" x2="19.5" y1="27.719" y2="27.719" gradientUnits="userSpaceOnUse"><stop class="zxezw9bhh"/><stop offset="1" class="iob9qrb7j"/></linearGradient><linearGradient id="iPkwVBb" x1="8.998" x2="8.998" y1="14.017" y2="24.688" gradientUnits="userSpaceOnUse"><stop class="v5dh7ebjb"/><stop offset="1" class="rjweixb-j"/></linearGradient><linearGradient id="icwz41g" x1="17.945" x2="17.945" y1="21.99" y2="13.5" gradientUnits="userSpaceOnUse"><stop class="mwgarcirp"/><stop offset="1" class="jmna7zq9j"/></linearGradient><linearGradient id="imSxPLd" x1="12.927" x2="16.986" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop offset=".575" class="b46sikbeh"/><stop offset="1" class="dwuc60e4g"/></linearGradient><linearGradient id="iT1Bt5b" x1="22.971" x2="22.971" y1="10.844" y2="11.625" gradientUnits="userSpaceOnUse"><stop class="gophtjlrd"/><stop offset="1" class="oajc4e91r"/></linearGradient><linearGradient id="ittBXyu" x1="14.937" x2="14.937" y1="12.99" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="mwgarcirp"/><stop offset="1" class="jmna7zq9j"/></linearGradient><linearGradient id="iy3X0xc" x1="9.914" x2="13.977" y1="8.163" y2="8.163" gradientUnits="userSpaceOnUse"><stop offset=".575" class="b46sikbeh"/><stop offset="1" class="dwuc60e4g"/></linearGradient><linearGradient id="iFnSpqb" x1="19.969" x2="19.969" y1="1.844" y2="2.625" gradientUnits="userSpaceOnUse"><stop class="gophtjlrd"/><stop offset="1" class="oajc4e91r"/></linearGradient><linearGradient id="iF8wpne" x1="23.125" x2="23.125" y1="21.313" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="dmxfl8-gi"/><stop offset="1" class="g-m88bsds"/></linearGradient><filter id="iEMAxhD" width=".75" height="17.747" x="13.24" y="12.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".125"/></filter><filter id="iPmbUUc" width=".75" height="8.501" x="16.203" y="21.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".125"/></filter><filter id="itPhFHd" width="3.991" height="9.113" x="19.039" y="20.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.517647 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7790"/></filter><filter id="iVv255m" width="3.996" height="11.963" x="7" y="14.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.517647 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7790"/></filter><filter id="i88e2Qd" width="9.49" height="11.24" x="15.76" y="10.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.615686 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7790"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_7790" result="effect2_innerShadow_28327_7790"/></filter><filter id="i9TdThe" width="9.5" height="11.24" x="12.75" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.615686 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7790"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_7790" result="effect2_innerShadow_28327_7790"/></filter><filter id="ivVX5wc" width="3.072" height="4.147" x="7.831" y="14.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".125"/></filter><filter id="iZUy8wb" width="1.05" height="5.987" x="22.1" y="20.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".2"/></filter><filter id="ieIEM8b" width="1.2" height="3.247" x="13.15" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".2"/></filter><filter id="iZEUl4v" width="1.2" height="3.247" x="16.15" y="18.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7790" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sheaf-of-rice" /></template>
<style>
.b45q3nbyi {
  stop-color: var(--svg-color--4b687c, #4B687C);
  stop-opacity: 0;
}

.b46sikbeh {
  stop-color: var(--svg-color--f0a43d, #F0A43D);
}

.b6-y9swko {
  stop-color: var(--svg-color--6aa136, #6AA136);
  stop-opacity: 0;
}

.bizo-8b8u {
  stop-color: var(--svg-color--99cc6b, #99CC6B);
}

.bykke4mhe {
  stop-color: var(--svg-color--337974, #337974);
}

.c9j967vxb {
  stop-color: var(--svg-color--99cc6b, #99CC6B);
  stop-opacity: 0;
}

.cmmzqiolf {
  stop-color: var(--svg-color--f6a340, #F6A340);
}

.d-gt9ofmd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.156 14.518c.807.255 2.422 1.223 2.422 3.498");
}

.d0dv-l24n {
  stop-color: var(--svg-color--8ec15d, #8EC15D);
  stop-opacity: 0;
}

.decz6kb8p {
  stop-color: var(--svg-color--4a6c9a, #4A6C9A);
  stop-opacity: 0;
}

.dmxfl8-gi {
  stop-color: var(--svg-color--8abe82, #8ABE82);
}

.dwuc60e4g {
  stop-color: var(--svg-color--f0a43d, #F0A43D);
  stop-opacity: 0;
}

.etqgr4-5n {
  d: path("M21.23 17h-2.19c-.41 0-.77-.32-.77-.74c-.01-.42.33-.76.75-.76h4.21c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-3.21c-.41 0-.77-.32-.77-.74c-.01-.42.33-.76.75-.76h4.21c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-4.43c-2.24 0-4.06 1.82-4.06 4.06v6.16c0 .41.32.77.74.77c.42.01.76-.33.76-.75v-1.81c0-.52.42-.94.94-.94h3.06c.42 0 .76-.34.75-.76a.78.78 0 0 0-.78-.73");
}

.f6it9ppwy {
  stop-color: var(--svg-color--6ea373, #6EA373);
}

.fq_0a2bjg {
  d: path("M10.906 24.964h2.375v1.016h-2.375z");
}

.ft5dv1b6b {
  fill: none;
}

.fyw8sxy3j {
  stop-color: var(--svg-color--8ec15d, #8EC15D);
}

.g-9g2nwtn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.615 12.576v16.997");
}

.g-m88bsds {
  stop-color: var(--svg-color--8abe82, #8ABE82);
  stop-opacity: 0;
}

.gd6vn0axr {
  stop-color: var(--svg-color--2c6e4a, #2C6E4A);
}

.gophtjlrd {
  stop-color: var(--svg-color--ffe338, #FFE338);
}

.gp_6pv_mk {
  stop-color: var(--svg-color--f6a340, #F6A340);
  stop-opacity: 0;
}

.gpn27h98q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.625 21.313v4.937");
}

.guf1291_d {
  stop-color: var(--svg-color--ffff65, #FFFF65);
  stop-opacity: 0;
}

.hz9eqsbio {
  stop-color: var(--svg-color--7f9771, #7F9771);
}

.idjszkboa {
  d: path("M16.578 28.984h2.797L19.055 30h-2.477z");
}

.iob9qrb7j {
  stop-color: var(--svg-color--2e7361, #2E7361);
  stop-opacity: 0;
}

.jjsf3-17u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.578 21.883v7.751");
}

.jmna7zq9j {
  stop-color: var(--svg-color--ffbd2f, #FFBD2F);
  stop-opacity: 0;
}

.l14zb5baa {
  stop-color: var(--svg-color--4a6c9a, #4A6C9A);
}

.lpfrhb-er {
  stop-color: var(--svg-color--577591, #577591);
}

.lti6v5gtk {
  stop-color: var(--svg-color--ffff65, #FFFF65);
}

.mgfda9-yg {
  d: path("M13.75 30h-.49c-.15 0-.26-.11-.26-.26V11h1v18.74c0 .15-.11.26-.25.26");
}

.mwgarcirp {
  stop-color: var(--svg-color--ffbd2f, #FFBD2F);
}

.n_ml7lbfi {
  fill: var(--svg-color--ffde50, #FFDE50);
  d: path("M21.23 17h-2.19c-.41 0-.77-.32-.77-.74c-.01-.42.33-.76.75-.76h4.21c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-3.21c-.41 0-.77-.32-.77-.74c-.01-.42.33-.76.75-.76h4.21c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-4.43c-2.24 0-4.06 1.82-4.06 4.06v6.16c0 .41.32.77.74.77c.42.01.76-.33.76-.75v-1.81c0-.52.42-.94.94-.94h3.06c.42 0 .76-.34.75-.76a.78.78 0 0 0-.78-.73");
}

.n4paw5bmo {
  d: path("M18.23 8h-2.38c-.41 0-.76-.32-.77-.74s.33-.76.75-.76h4.4c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-3.4c-.41 0-.76-.32-.77-.74s.33-.76.75-.76h4.4c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-4.44c-2.24 0-4.06 1.82-4.06 4.06v6.16c0 .41.32.77.74.77c.42.01.76-.33.76-.75v-1.8c0-.52.42-.94.94-.94h3.06c.42 0 .76-.34.75-.76a.764.764 0 0 0-.77-.74");
}

.nvrb7d_wj {
  stop-color: var(--svg-color--6aa136, #6AA136);
}

.o-yxeybvr {
  stop-color: var(--svg-color--77a947, #77A947);
  stop-opacity: 0;
}

.oajc4e91r {
  stop-color: var(--svg-color--ffe338, #FFE338);
  stop-opacity: 0;
}

.otul22bbw {
  stop-color: var(--svg-color--577591, #577591);
  stop-opacity: 0;
}

.pz-gs_6iq {
  d: path("M17 16h-1v13.67c0 .18.15.33.33.33h.35c.17 0 .32-.15.32-.33z");
}

.q-ccmfbvo {
  stroke: var(--svg-color--ffd25b, #FFD25B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.75 21.313v-2.047");
}

.q2gb_ds8v {
  stop-color: var(--svg-color--417f8b, #417F8B);
}

.q60xm5poj {
  stop-color: var(--svg-color--66a55d, #66A55D);
}

.qgtesx2ew {
  stop-color: var(--svg-color--86b14b, #86B14B);
}

.qmg-a-caa {
  stop-color: var(--svg-color--5b9691, #5B9691);
}

.qmt6r0bac {
  stroke: var(--svg-color--ffd25b, #FFD25B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.75 12.25v-2.047");
}

.quxsmxa9j {
  d: path("M10.996 17.812A3.994 3.994 0 0 0 7.47 14.02a.416.416 0 0 0-.47.41v7.55a4 4 0 0 0 3.996 4z");
}

.rjweixb-j {
  stop-color: var(--svg-color--5f8e80, #5F8E80);
}

.smw1tskmy {
  stop-color: var(--svg-color--77a947, #77A947);
}

.tibx-_m4a {
  stop-color: var(--svg-color--527791, #527791);
}

.tq-h-bbvk {
  stop-color: var(--svg-color--7f9771, #7F9771);
  stop-opacity: 0;
}

.v5dh7ebjb {
  stop-color: var(--svg-color--7eb342, #7EB342);
}

.vfd6kab6u {
  fill: var(--svg-color--ffde50, #FFDE50);
  d: path("M18.23 8h-2.38c-.41 0-.76-.32-.77-.74s.33-.76.75-.76h4.4c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-3.4c-.41 0-.76-.32-.77-.74s.33-.76.75-.76h4.4c.41 0 .77-.32.77-.74a.745.745 0 0 0-.75-.76h-4.44c-2.24 0-4.06 1.82-4.06 4.06v6.16c0 .41.32.77.74.77c.42.01.76-.33.76-.75v-1.8c0-.52.42-.94.94-.94h3.06c.42 0 .76-.34.75-.76a.764.764 0 0 0-.77-.74");
}

.wgngpd2bw {
  stop-color: var(--svg-color--66a55d, #66A55D);
  stop-opacity: 0;
}

.xyshjxbgl {
  d: path("M19.039 30v-5.41a3.994 3.994 0 0 1 3.52-3.699c.25-.03.47.16.47.41V26a4 4 0 0 1-3.99 4");
}

.yzpr0ninf {
  stop-color: var(--svg-color--6da336, #6DA336);
}

.zduypibhf {
  stop-color: var(--svg-color--94be59, #94BE59);
}

.zxezw9bhh {
  stop-color: var(--svg-color--2e7361, #2E7361);
}

</style>
