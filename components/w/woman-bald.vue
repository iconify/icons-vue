<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2x7cWc)"><path fill="url(#iHJRB9d)" class="thb4xabvg"/></g><g filter="url(#iXRy5Sc)"><path fill="url(#iJVqezC)" class="mm24yqbrt"/></g><g filter="url(#iGUu8od)"><path class="lhwdpmbro"/><path fill="url(#iji3s8b)" class="j7cx-0ift"/></g><g filter="url(#iiNDnIc)"><path class="ka7fwpeao"/><path fill="url(#iRyvtCb)" class="k47c-ph6f"/></g><g filter="url(#i38iZIb)"><path fill="url(#i5ouvte)" class="l19c4kb8p"/><path fill="url(#iBrXWAc)" class="l19c4kb8p"/><path fill="url(#i5RkHOo)" class="l19c4kb8p"/><path fill="url(#iz5ROZy)" class="l19c4kb8p"/><path fill="url(#iNu8Bld)" class="l19c4kb8p"/><path fill="url(#iv57rKc)" class="l19c4kb8p"/></g><g filter="url(#ijqmIMd)"><path class="eyq1kcl6d"/></g><g filter="url(#i3A3hpb)"><path fill="url(#i75M2Sb)" class="cit24l8vo"/><path fill="url(#iXM7W7d)" class="cit24l8vo"/><path fill="url(#itzGOne)" class="cit24l8vo"/><path fill="url(#inPs83d)" class="cit24l8vo"/></g><path fill="url(#icY6Kfd)" class="cit24l8vo"/><path fill="url(#im6C59d)" class="cit24l8vo"/><path stroke="url(#iUTMYfe)" class="tol-_v9_t"/><g filter="url(#i3VUp4b)"><path class="cut3x3vsv"/></g><g filter="url(#iohCA3S)"><path class="egtskfb2w"/></g><path class="rzbg9ktoz"/><path fill="url(#iFGn1Sb)" class="lmvsc4jwp"/><path class="o4bvoubwn"/><g filter="url(#i1xAOvb)"><path class="l74zifb5z"/><path fill="url(#ijeSMXj)" class="ud42h1b1a"/></g><g filter="url(#i19nAeb)"><path fill="url(#iDkm1pc)" class="hr82j97xi"/></g><path class="nbougwb_e"/><path fill="url(#iKejqRd)" class="ve1fk2yhv"/><path class="vg1cojbhr"/><g filter="url(#iYPTmnb)"><path fill="url(#iLcp6Iy)" class="njpr_4bqf"/></g><g filter="url(#ibt5K8c)"><ellipse transform="rotate(-27.914 11.462 16.532)" class="wkwl1yohp"/><ellipse fill="url(#iInQLGe)" transform="rotate(-27.914 11.462 16.532)" class="bmbbi19pd"/></g><g filter="url(#ihMHAAd)"><path class="y6p1gzb0y"/></g><g filter="url(#i5RNroN)"><path clip-rule="evenodd" class="z1w99qb8v"/></g><g filter="url(#iAgLcPc)"><path class="ntmk_rpcl"/></g><g filter="url(#iwUmhlD)"><path class="rvh0r8bdl"/></g><defs><filter id="i2x7cWc" width="6.15" height="6.25" x="4.3" y="14.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="iXRy5Sc" width="6" height="6.25" x="22.036" y="14.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="iGUu8od" width="5.005" height="5.005" x="22.533" y="15.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".25"/></filter><filter id="iiNDnIc" width="5.005" height="5.005" x="4.833" y="15.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".25"/></filter><filter id="i38iZIb" width="19.103" height="24.601" x="6.682" y="4.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.643137 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="ijqmIMd" width="4.5" height="6" x="13.407" y="16.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".25"/></filter><filter id="i3A3hpb" width="4" height="5.5" x="14.036" y="16.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".125"/></filter><filter id="i3VUp4b" width="5.423" height="2.397" x="17.965" y="15.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="iohCA3S" width="5.423" height="2.397" x="8.684" y="15.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="i1xAOvb" width="1.294" height="1.125" x="18.822" y="15.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".05"/></filter><filter id="i19nAeb" width="1.316" height="1.357" x="20.474" y="16.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".1"/></filter><filter id="iYPTmnb" width="1.493" height="1.594" x="12.191" y="16.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".1"/></filter><filter id="ibt5K8c" width="1.529" height="1.141" x="10.697" y="15.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".05"/></filter><filter id="ihMHAAd" width="4.4" height="1.861" x="8.936" y="12.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="i5RNroN" width="4.4" height="1.861" x="19.036" y="12.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19261"/></filter><filter id="iAgLcPc" width="4.296" height="1.904" x="19.052" y="12.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".2"/></filter><filter id="iwUmhlD" width="4.296" height="1.904" x="8.888" y="12.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19261" stdDeviation=".2"/></filter><radialGradient id="iJVqezC" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 54.816 -45.08)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iji3s8b" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 63.324 -59.575)scale(2.43229)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iRyvtCb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00258 0 0 -1.9156 7.336 17.824)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i5ouvte" cx="0" cy="0" r="1" gradientTransform="matrix(-9.375 5.12501 -5.03498 -9.2103 21.296 15.827)" gradientUnits="userSpaceOnUse"><stop class="zaigj4bqx"/><stop offset="1" class="p_d2w15fs"/></radialGradient><radialGradient id="iBrXWAc" cx="0" cy="0" r="1" gradientTransform="rotate(145.635 9.259 8.007)scale(10.2973 9.98192)" gradientUnits="userSpaceOnUse"><stop class="siaqk_q5i"/><stop offset="1" class="wu7nm6bxi"/></radialGradient><radialGradient id="i5RkHOo" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.358 2.093)scale(2.5625)" gradientUnits="userSpaceOnUse"><stop class="w93s4ccsu"/><stop offset="1" class="ont0lix4u"/></radialGradient><radialGradient id="iz5ROZy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.01556 3.0625 0 20.171 16.78)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="zu8786bxc"/><stop offset="1" class="p0qi0obsf"/></radialGradient><radialGradient id="iNu8Bld" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03125 -1.93296 0 11.765 17.483)" gradientUnits="userSpaceOnUse"><stop class="biyr2obnk"/><stop offset="1" class="r00qa_bka"/></radialGradient><radialGradient id="iv57rKc" cx="0" cy="0" r="1" gradientTransform="rotate(106.285 4.707 13.693)scale(17.385 17.0803)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="hryzxfb8e"/><stop offset=".96" class="gers9wbjb"/></radialGradient><radialGradient id="iXM7W7d" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 16.364 3.479)scale(4.74883 2.71734)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="im6C59d" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 5.16 12.407)scale(2.93624 3.93288)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iFGn1Sb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 20.104 16.71)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijeSMXj" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.679 16.867)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKejqRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.968 16.71)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iInQLGe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.143 2.931)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iHJRB9d" x1="4.3" x2="9.817" y1="17.986" y2="17.986" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i75M2Sb" x1="16.036" x2="16.036" y1="21.624" y2="16.624" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="itzGOne" x1="14.085" x2="15.678" y1="20.202" y2="20.397" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="inPs83d" x1="16.036" x2="16.036" y1="21.795" y2="20.657" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="icY6Kfd" x1="16.182" x2="16.182" y1="21.746" y2="21.486" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iUTMYfe" x1="14.677" x2="15.521" y1="24.549" y2="22.924" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iDkm1pc" x1="21.555" x2="20.97" y1="16.811" y2="17.171" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLcp6Iy" x1="13.354" x2="12.77" y1="16.811" y2="17.171" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bald" /></template>
<style>
.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.biyr2obnk {
  stop-color: var(--svg-color--ffbb2a, #FFBB2A);
}

.bmbbi19pd {
  cx: 11.462px;
  cy: 16.532px;
  rx: 0.726px;
  ry: 0.368px;
}

.cit24l8vo {
  d: path("m15.323 17.15l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cut3x3vsv {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.165 16.763c.495-.87 1.247-1.558 2.867-1.558c.709 0 1.392.196 2 .687c.5.405.434.924.046 1.118l-1.037.591c-1.215-.392-2.56-.445-3.876-.838");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.egtskfb2w {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.907 16.763c-.495-.87-1.247-1.558-2.866-1.558c-.71 0-1.393.196-2 .687c-.502.405-.435.924-.046 1.118l1.036.591c1.215-.392 2.56-.445 3.876-.838");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eyq1kcl6d {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.228 17.626l-1.275 3.17a1.005 1.005 0 0 0 .97 1.303h1.467c.688 0 1.173-.662.97-1.303l-.99-3.17c-.213-.702-.92-.702-1.142 0");
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.gers9wbjb {
  stop-color: var(--svg-color--d67760, #D67760);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hr82j97xi {
  d: path("M21.59 17.266a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.hryzxfb8e {
  stop-color: var(--svg-color--d67760, #D67760);
  stop-opacity: 0;
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j7cx-0ift {
  d: path("M25.036 19.826a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.k47c-ph6f {
  d: path("M7.336 19.826a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.ka7fwpeao {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M7.336 19.826a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.l19c4kb8p {
  d: path("M6.682 20.222c.23 5.225 4.31 8.733 9.291 8.733c4.98 0 9.061-3.508 9.29-8.733l.022-8.722c0-3.3-2.057-5.92-6.3-6.736c-1.6-.211-4.5-.214-6 0c-4.242.816-6.3 3.435-6.3 6.736z");
}

.l74zifb5z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.986 16.173c.118.158-.13.352-.411.562c-.282.211-.491.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.lhwdpmbro {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M25.036 19.826a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmvsc4jwp {
  d: path("M20.108 15.821a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mm24yqbrt {
  d: path("M25.036 20.824a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.nbougwb_e {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.578 15.314c-1.217 0-2.246.84-2.526 1.974a.51.51 0 0 0 .5.636h4.159a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.njpr_4bqf {
  d: path("M13.484 17.29c0-.538-.437-.897-.555-1.005l-.538.52l.33.674z");
}

.ntmk_rpcl {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.652 13.4c.601-.146 2.097-.073 3.096.642");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o4bvoubwn {
  fill: var(--svg-color--000, #000);
  d: path("M19.155 17.485c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.44");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ont0lix4u {
  stop-color: var(--svg-color--f0942d, #F0942D);
  stop-opacity: 0;
}

.p_d2w15fs {
  stop-color: var(--svg-color--fca62b, #FCA62B);
}

.p0qi0obsf {
  stop-color: var(--svg-color--ffbc31, #FFBC31);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r00qa_bka {
  stop-color: var(--svg-color--ffbb2a, #FFBB2A);
  stop-opacity: 0;
}

.rvh0r8bdl {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.584 13.4c-.601-.146-2.096-.073-3.096.642");
}

.rzbg9ktoz {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.494 15.314c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.siaqk_q5i {
  stop-color: var(--svg-color--ffec48, #FFEC48);
}

.thb4xabvg {
  d: path("M7.3 20.824a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.tol-_v9_t {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.409 22.565a.34.34 0 0 0-.41.072a.32.32 0 0 0-.034.409a3.65 3.65 0 0 0 3.07 1.678c1.29 0 2.422-.672 3.072-1.678a.33.33 0 0 0-.035-.413a.34.34 0 0 0-.409-.068a5.6 5.6 0 0 1-2.627.637a5.6 5.6 0 0 1-2.627-.637Z");
}

.ud42h1b1a {
  d: path("M19.986 16.173c.118.158-.13.352-.411.562c-.282.211-.491.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ve1fk2yhv {
  d: path("M11.964 15.821a1.664 1.664 0 0 0-1.604 2.103h3.215c.038-.144.06-.288.06-.44a1.675 1.675 0 0 0-1.671-1.663");
}

.vg1cojbhr {
  fill: var(--svg-color--000, #000);
  d: path("M12.917 17.485a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.038.31.106.439h1.686a.95.95 0 0 0 .114-.44");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w93s4ccsu {
  stop-color: var(--svg-color--f0942d, #F0942D);
}

.wkwl1yohp {
  cx: 11.462px;
  cy: 16.532px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.wu7nm6bxi {
  stop-color: var(--svg-color--ffec48, #FFEC48);
  stop-opacity: 0;
}

.y6p1gzb0y {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m9.701 14.509l-.008.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.183-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.z1w99qb8v {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m22.993 13.656l-.257.429za.5.5 0 0 1-.513.858h-.001l-.008-.005l-.04-.023a5 5 0 0 0-.809-.338c-.542-.172-1.256-.302-2-.17a.5.5 0 0 1-.173-.985c.957-.17 1.843 0 2.477.203a6 6 0 0 1 .98.411l.06.034l.018.01l.006.003l.002.001z");
}

.zaigj4bqx {
  stop-color: var(--svg-color--ffe647, #FFE647);
}

.zu8786bxc {
  stop-color: var(--svg-color--ffbc31, #FFBC31);
}

</style>
