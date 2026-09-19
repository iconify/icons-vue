<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iiFceOc)"><path fill="url(#iEUHcCc)" class="lxpud0b2g"/></g><g filter="url(#ifWM8Rc)"><path fill="url(#i7DkpDK)" class="zpkcqzbhd"/><path fill="url(#iavlbdc)" class="zpkcqzbhd"/></g><g filter="url(#ihhR2Je)"><path class="tcygywbwb"/><path fill="url(#iqPkeRC)" class="cdr5chbcr"/></g><g filter="url(#iuwDBMe)"><path class="fvhk-d0iq"/><path fill="url(#i7udopb)" class="d70a2rbsc"/></g><g filter="url(#iWNtVSb)"><path fill="url(#i6iwFoi)" class="m_6afkb3g"/><path fill="url(#iMMw1sC)" class="m_6afkb3g"/><path fill="url(#ijwegLc)" class="m_6afkb3g"/><path fill="url(#iFf3fZc)" class="m_6afkb3g"/><path fill="url(#iE8aFEb)" class="m_6afkb3g"/><path fill="url(#iacGPYd)" class="m_6afkb3g"/></g><path fill="url(#i15RHLe)" class="m_6afkb3g"/><path fill="url(#iqGfecb)" class="m_6afkb3g"/><g filter="url(#ioyGEmb)"><path class="c2wmeqnam"/></g><g filter="url(#i0uHi7d)"><path class="h7lnuiboe"/><path fill="url(#iWktLGc)" class="vkidrxlnj"/><path fill="url(#iZJl3Wb)" class="vkidrxlnj"/><path fill="url(#iokU24c)" class="vkidrxlnj"/></g><path fill="url(#iu3DdQd)" class="vkidrxlnj"/><path fill="url(#iqV6DCc)" class="vkidrxlnj"/><path stroke="url(#iwG1wWb)" class="v35_t3bfi"/><g filter="url(#iNgCz1b)"><path class="ill15etje"/></g><g filter="url(#iwBVSNb)"><path class="sceye73jp"/></g><path class="kfcuxjbdg"/><path fill="url(#iZKweId)" class="p2ix1lgev"/><path class="wvrl9dw2w"/><g filter="url(#iqlgRTc)"><path class="meqe2nbsh"/><path fill="url(#iZs9X2i)" class="pnvvyw_la"/></g><g filter="url(#ioBQb1t)"><path fill="url(#iBNayId)" class="w-3vbuboa"/></g><path class="owk96x87f"/><path fill="url(#i2PfKie)" class="mmo2g_bgc"/><path class="vgurtx5se"/><g filter="url(#iv3O0Tb)"><path fill="url(#igZb7lW)" class="n1a0z-bmq"/></g><g filter="url(#igZy3Qc)"><ellipse transform="rotate(-27.914 11.478 16.667)" class="kpfbnkb4n"/><ellipse fill="url(#i9d5wxc)" transform="rotate(-27.914 11.478 16.667)" class="i16h9bcoj"/></g><g filter="url(#izLs5he)"><path fill="url(#i46qBzc)" class="nmdo8q_ty"/></g><g filter="url(#i4ydTwc)"><path class="ld5jewh-c"/></g><g filter="url(#im0kPod)"><path clip-rule="evenodd" class="ddtla2luz"/></g><g filter="url(#iOn3djb)"><path class="wupoedcdt"/></g><g filter="url(#itSzMHe)"><path class="spmti7lss"/></g><defs><radialGradient id="i7DkpDK" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 55.137 -45.05)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iavlbdc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85938 .53125 -.2793 .97754 25.49 14.637)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iqPkeRC" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 63.71 -59.553)scale(2.43229)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i7udopb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26873 0 0 -2.17018 7.352 17.96)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="i6iwFoi" cx="0" cy="0" r="1" gradientTransform="matrix(-9.375 5.12501 -6.13482 -11.2222 21.313 15.962)" gradientUnits="userSpaceOnUse"><stop class="qn8tvf7_f"/><stop offset="1" class="qv6l1jf8l"/></radialGradient><radialGradient id="iMMw1sC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60062 2.93086 0 11.595 15.967)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="k0vr-abgw"/><stop offset="1" class="y4sdqpr4t"/></radialGradient><radialGradient id="ijwegLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60062 3.4675 0 20.636 15.802)" gradientUnits="userSpaceOnUse"><stop class="sko6_k-0v"/><stop offset="1" class="fvoljv6ez"/></radialGradient><radialGradient id="iFf3fZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03125 -1.93296 0 11.781 17.619)" gradientUnits="userSpaceOnUse"><stop class="hfvyq_rrq"/><stop offset="1" class="ra1c3f1wl"/></radialGradient><radialGradient id="iE8aFEb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93756 15.94082 -17.37414 -5.38152 19.188 13.15)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="j0qje-b1c"/><stop offset="1" class="oq2z0gbab"/></radialGradient><radialGradient id="iacGPYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.9375 -4.04687 0 17.5 4.212)" gradientUnits="userSpaceOnUse"><stop class="ncgvrg24k"/><stop offset="1" class="k_ay_jb9c"/></radialGradient><radialGradient id="i15RHLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.8163 4.08668 -8.49893 3.7773 9.614 5.977)" gradientUnits="userSpaceOnUse"><stop class="vu-ueu99y"/><stop offset="1" class="jg8h3tb7u"/></radialGradient><radialGradient id="iqGfecb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.02652 9.03985 -8.40484 -7.4627 25.302 6.435)" gradientUnits="userSpaceOnUse"><stop class="vwdr7db7z"/><stop offset="1" class="y-xyj_bta"/></radialGradient><radialGradient id="iWktLGc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 16.423 3.54)scale(4.74883 2.71734)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iqV6DCc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 5.147 12.477)scale(2.93624 3.93288)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iZKweId" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 20.12 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZs9X2i" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.695 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2PfKie" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.984 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9d5wxc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.218 2.991)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iiFceOc" width="6.15" height="6.25" x="4.316" y="14.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="ifWM8Rc" width="6" height="6.25" x="22.052" y="14.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="ihhR2Je" width="5.005" height="5.005" x="22.55" y="15.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".25"/></filter><filter id="iuwDBMe" width="4.805" height="4.805" x="4.95" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".2"/></filter><filter id="iWNtVSb" width="19.853" height="24.601" x="6.699" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".25"/><feGaussianBlur stdDeviation=".875"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.631373 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="ioyGEmb" width="4.5" height="5.719" x="13.423" y="16.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".25"/></filter><filter id="i0uHi7d" width="4" height="5.5" x="14.052" y="16.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".125"/></filter><filter id="iNgCz1b" width="5.423" height="2.397" x="17.982" y="15.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="iwBVSNb" width="5.423" height="2.397" x="8.7" y="15.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="iqlgRTc" width="1.294" height="1.125" x="18.838" y="16.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".05"/></filter><filter id="ioBQb1t" width="1.316" height="1.357" x="20.491" y="16.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".1"/></filter><filter id="iv3O0Tb" width="1.493" height="1.594" x="12.207" y="16.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".1"/></filter><filter id="igZy3Qc" width="1.529" height="1.141" x="10.713" y="16.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".05"/></filter><filter id="izLs5he" width="12.86" height="11.918" x="14.098" y="3.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation="1.25"/></filter><filter id="i4ydTwc" width="4.4" height="1.861" x="8.952" y="12.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="im0kPod" width="4.4" height="1.861" x="19.052" y="12.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19254"/></filter><filter id="iOn3djb" width="4.296" height="1.904" x="19.068" y="12.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".2"/></filter><filter id="itSzMHe" width="4.296" height="1.904" x="8.904" y="12.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19254" stdDeviation=".2"/></filter><linearGradient id="iEUHcCc" x1="4.316" x2="9.834" y1="18.122" y2="18.122" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iZJl3Wb" x1="14.101" x2="15.694" y1="20.338" y2="20.533" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iokU24c" x1="16.052" x2="16.052" y1="21.931" y2="20.793" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iu3DdQd" x1="16.198" x2="16.198" y1="21.882" y2="21.622" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iwG1wWb" x1="14.693" x2="15.537" y1="24.684" y2="23.059" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="iBNayId" x1="21.571" x2="20.986" y1="16.946" y2="17.307" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igZb7lW" x1="13.371" x2="12.786" y1="16.946" y2="17.307" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i46qBzc" x1="19.591" x2="25.45" y1="12.411" y2="5.097" gradientUnits="userSpaceOnUse"><stop class="g31rn7qdq"/><stop offset="1" class="mi_x_zbkv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bald-medium-light" /></template>
<style>
.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.c2wmeqnam {
  fill: var(--svg-color--c28178, #C28178);
  d: path("M15.244 17.761L13.97 20.65a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.303l-.991-2.889c-.212-.702-.92-.702-1.142 0");
}

.cdr5chbcr {
  d: path("M25.052 19.962a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d70a2rbsc {
  d: path("M7.352 19.962a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.ddtla2luz {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m23.01 13.791l-.258.43za.5.5 0 0 1-.514.858l-.008-.005l-.04-.022a5 5 0 0 0-.809-.338c-.542-.173-1.255-.302-1.999-.171a.5.5 0 1 1-.174-.985c.957-.169 1.843.001 2.477.203a6 6 0 0 1 .98.412l.061.033l.018.01l.005.004z");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.ft5dv1b6b {
  fill: none;
}

.fvhk-d0iq {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M7.352 19.962a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.fvoljv6ez {
  stop-color: var(--svg-color--e5a690, #E5A690);
  stop-opacity: 0;
}

.g31rn7qdq {
  stop-color: var(--svg-color--ffceab, #FFCEAB);
}

.h7lnuiboe {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.34 17.286l-.992 3.17a1.005 1.005 0 0 0 .971 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.hfvyq_rrq {
  stop-color: var(--svg-color--d7a285, #D7A285);
}

.i16h9bcoj {
  cx: 11.478px;
  cy: 16.667px;
  rx: 0.726px;
  ry: 0.368px;
}

.ill15etje {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.182 16.898c.494-.87 1.247-1.558 2.866-1.558c.709 0 1.392.197 2 .688c.501.405.434.923.046 1.117l-1.037.592c-1.215-.393-2.559-.446-3.875-.839");
}

.j0qje-b1c {
  stop-color: var(--svg-color--b36d8f, #B36D8F);
  stop-opacity: 0;
}

.jg8h3tb7u {
  stop-color: var(--svg-color--c29c80, #C29C80);
  stop-opacity: 0;
}

.k_ay_jb9c {
  stop-color: var(--svg-color--dac0aa, #DAC0AA);
  stop-opacity: 0;
}

.k0vr-abgw {
  stop-color: var(--svg-color--c3857d, #C3857D);
}

.kfcuxjbdg {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.51 15.45c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.kpfbnkb4n {
  cx: 11.478px;
  cy: 16.667px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ld5jewh-c {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m9.718 14.644l-.008.005h-.001a.5.5 0 0 1-.514-.858h.001l.002-.001l.006-.004l.017-.01l.06-.033a6 6 0 0 1 .98-.411c.635-.203 1.522-.373 2.478-.204a.5.5 0 1 1-.174.985c-.743-.131-1.457-.002-1.998.171a5 5 0 0 0-.85.36");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxpud0b2g {
  d: path("M7.316 20.959a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.m_6afkb3g {
  d: path("M6.699 20.357c.23 5.225 4.31 8.734 9.29 8.734c4.981 0 9.061-3.509 9.291-8.734l.021-8.722c0-3.3-2.057-5.92-6.3-6.735c-1.6-.212-4.5-.215-6 0c-4.242.815-6.3 3.435-6.3 6.735z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meqe2nbsh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.002 16.308c.118.159-.13.352-.411.563c-.282.21-.49.359-.61.2c-.118-.159.014-.458.296-.668s.606-.253.725-.095");
}

.mi_x_zbkv {
  stop-color: var(--svg-color--ffceab, #FFCEAB);
  stop-opacity: 0;
}

.mmo2g_bgc {
  d: path("M11.98 15.957a1.664 1.664 0 0 0-1.603 2.102h3.214c.038-.144.06-.287.06-.439a1.675 1.675 0 0 0-1.67-1.664");
}

.n1a0z-bmq {
  d: path("M13.5 17.425c0-.538-.437-.896-.555-1.005l-.538.52l.331.674z");
}

.ncgvrg24k {
  stop-color: var(--svg-color--dac0aa, #DAC0AA);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nmdo8q_ty {
  d: path("m17.296 9.315l3.25-3.071c2.938 1.109 3.735 4.062 3.913 5.447l-5.041 1.39a2.227 2.227 0 0 1-2.122-3.766");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oq2z0gbab {
  stop-color: var(--svg-color--b36d8f, #B36D8F);
}

.owk96x87f {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.595 15.45c-1.218 0-2.247.84-2.527 1.974a.51.51 0 0 0 .5.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.p2ix1lgev {
  d: path("M20.124 15.957a1.664 1.664 0 0 1 1.604 2.102h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnvvyw_la {
  d: path("M20.002 16.308c.118.159-.13.352-.411.563c-.282.21-.49.359-.61.2c-.118-.159.014-.458.296-.668s.606-.253.725-.095");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qn8tvf7_f {
  stop-color: var(--svg-color--fec5a0, #FEC5A0);
}

.qv6l1jf8l {
  stop-color: var(--svg-color--d59e85, #D59E85);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.ra1c3f1wl {
  stop-color: var(--svg-color--d7a285, #D7A285);
  stop-opacity: 0;
}

.sceye73jp {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.923 16.898c-.495-.87-1.247-1.558-2.866-1.558c-.709 0-1.393.197-2 .688c-.501.405-.434.923-.046 1.117l1.037.592c1.215-.393 2.559-.446 3.875-.839");
}

.sko6_k-0v {
  stop-color: var(--svg-color--e5a690, #E5A690);
}

.spmti7lss {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.6 13.536c-.6-.147-2.096-.074-3.096.642");
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.tcygywbwb {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M25.052 19.962a2.003 2.003 0 1 0 0-4.006a2.003 2.003 0 0 0 0 4.006");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.v35_t3bfi {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.425 22.7a.34.34 0 0 0-.41.073a.32.32 0 0 0-.034.408a3.65 3.65 0 0 0 3.071 1.678a3.65 3.65 0 0 0 3.071-1.678a.33.33 0 0 0-.034-.412a.34.34 0 0 0-.41-.069a5.6 5.6 0 0 1-2.627.637a5.6 5.6 0 0 1-2.627-.636Z");
}

.vgurtx5se {
  fill: var(--svg-color--000, #000);
  d: path("M12.933 17.62a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.038.31.106.439h1.687a.95.95 0 0 0 .113-.439");
}

.vkidrxlnj {
  d: path("m15.34 17.286l-.992 3.17a1.005 1.005 0 0 0 .971 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.vu-ueu99y {
  stop-color: var(--svg-color--c29c80, #C29C80);
}

.vwdr7db7z {
  stop-color: var(--svg-color--fccba0, #FCCBA0);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w-3vbuboa {
  d: path("M21.606 17.401a1.57 1.57 0 0 0-.431-.862l-.485.531l.22.426z");
}

.wupoedcdt {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.668 13.536c.602-.147 2.097-.074 3.097.642");
}

.wvrl9dw2w {
  fill: var(--svg-color--000, #000);
  d: path("M19.171 17.62a.95.95 0 0 1 .953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.114-.439");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.y-xyj_bta {
  stop-color: var(--svg-color--fccba0, #FCCBA0);
  stop-opacity: 0;
}

.y4sdqpr4t {
  stop-color: var(--svg-color--c3857d, #C3857D);
  stop-opacity: 0;
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.zpkcqzbhd {
  d: path("M25.052 20.959a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
