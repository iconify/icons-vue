<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEtREFc)" class="q3rp4efeb"/><path fill="url(#iuFEPAe)" class="q3rp4efeb"/><path fill="url(#ilj4GRc)" class="q3rp4efeb"/><g filter="url(#iux3Vbb)"><path stroke="url(#iwtrLLb)" class="jxd4macfy"/></g><path fill="url(#iDvJzke)" class="wjheywb8l"/><path fill="url(#ibiSk8q)" class="wjheywb8l"/><path fill="url(#ijByHlc)" class="wjheywb8l"/><path fill="url(#iinyc4V)" class="wjheywb8l"/><path fill="url(#iOvMJ8d)" class="bzjyogscy"/><g filter="url(#irMBIie)"><path fill="url(#iwOOoVb)" class="a3q83gb4l"/></g><path fill="url(#iHzUzUc)" class="a3q83gb4l"/><defs><radialGradient id="iEtREFc" cx="0" cy="0" r="1" gradientTransform="rotate(46.167 -4.095 16.54)scale(20.9368 25.5307)" gradientUnits="userSpaceOnUse"><stop class="a6rtcdbju"/><stop offset=".342" class="dweqcjfwy"/><stop offset="1" class="zc4x5xyel"/></radialGradient><radialGradient id="ilj4GRc" cx="0" cy="0" r="1" gradientTransform="rotate(86.37 6.115 11.713)scale(21.6099 28.0052)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="acdcf99-r"/><stop offset="1" class="dxssq6bsq"/></radialGradient><radialGradient id="ijByHlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.56232 12.3092 0 18.967 10.923)" gradientUnits="userSpaceOnUse"><stop offset=".746" class="rj6sl96xk"/><stop offset="1" class="z-yl_xytl"/></radialGradient><radialGradient id="iinyc4V" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06814 3.56653 -4.29108 -4.8946 22.879 7.822)" gradientUnits="userSpaceOnUse"><stop class="x72912byk"/><stop offset="1" class="svnkaacda"/></radialGradient><radialGradient id="iwOOoVb" cx="0" cy="0" r="1" gradientTransform="matrix(-19.0818 0 0 -24.2835 22.414 26.614)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="fonheiqlz"/><stop offset="1" class="fosxapi2e"/></radialGradient><radialGradient id="iHzUzUc" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 -2.783 18.025)scale(4.1103 9.10443)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="wrn2o0bzh"/><stop offset="1" class="jfbqwymbm"/></radialGradient><linearGradient id="iuFEPAe" x1="30.68" x2="28.674" y1="19.357" y2="19.357" gradientUnits="userSpaceOnUse"><stop class="b0-ny1bjx"/><stop offset="1" class="r4c4wlbjv"/></linearGradient><linearGradient id="iwtrLLb" x1="19.424" x2="30.29" y1="7.822" y2="17.853" gradientUnits="userSpaceOnUse"><stop offset=".641" class="soq-7oghd"/><stop offset="1" class="kryq8jb1n"/></linearGradient><linearGradient id="iDvJzke" x1="16.015" x2="16.015" y1="10.89" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="cr-q-hb3t"/><stop offset="1" class="im_kpibne"/></linearGradient><linearGradient id="ibiSk8q" x1="9.727" x2="15.771" y1="4" y2="9.223" gradientUnits="userSpaceOnUse"><stop offset=".213" class="mfy37wuzz"/><stop offset=".375" class="z-yl_xytl"/><stop offset="1" class="rj6sl96xk"/></linearGradient><linearGradient id="iOvMJ8d" x1="3.422" x2="16.672" y1="12.204" y2="23.642" gradientUnits="userSpaceOnUse"><stop class="kz73lyboe"/><stop offset="1" class="t4nv07b4q"/></linearGradient><filter id="iux3Vbb" width="15.529" height="15.474" x="16.145" y="4.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4930" stdDeviation="1"/></filter><filter id="irMBIie" width="28.219" height="8.219" x="2.016" y="21.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.298039 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4930"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mountain" /></template>
<style>
.a3q83gb4l {
  d: path("M10.997 23.037c-3.952-1.362-6.856-1.093-8.981-.554v7.53h27.968v-7.535c-3.173 1.407-6.579 2.565-9.991 2.565s-5.045-.644-8.996-2.006");
}

.a6rtcdbju {
  stop-color: var(--svg-color--644e46, #644E46);
}

.acdcf99-r {
  stop-color: var(--svg-color--9d6f60, #9D6F60);
  stop-opacity: 0;
}

.b0-ny1bjx {
  stop-color: var(--svg-color--987469, #987469);
}

.bzjyogscy {
  d: path("M5.952 11.257c-.898 1.09-3.015 3.62-3.961 4.748v9.322h20.965l-7.14-7.17c-1.065-1.077-2.47-1.93-4.116-1.93c-1.721 0-2.724-1.467-2.724-3.204c0-1.392-.015-2.26 0-3.188c-.913 0-1.901.06-3.024 1.422");
}

.cr-q-hb3t {
  stop-color: var(--svg-color--d4cad6, #D4CAD6);
}

.dweqcjfwy {
  stop-color: var(--svg-color--9a6b5b, #9A6B5B);
}

.dxssq6bsq {
  stop-color: var(--svg-color--9d6f60, #9D6F60);
}

.fonheiqlz {
  stop-color: var(--svg-color--3ccc79, #3CCC79);
}

.fosxapi2e {
  stop-color: var(--svg-color--3b9b76, #3B9B76);
}

.ft5dv1b6b {
  fill: none;
}

.im_kpibne {
  stop-color: var(--svg-color--dedde8, #DEDDE8);
}

.jfbqwymbm {
  stop-color: var(--svg-color--42b671, #42B671);
  stop-opacity: 0;
}

.jxd4macfy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19.145 7.376l9.53 9.474");
}

.kryq8jb1n {
  stop-color: var(--svg-color--bb8672, #BB8672);
  stop-opacity: 0;
}

.kz73lyboe {
  stop-color: var(--svg-color--4a3b36, #4A3B36);
}

.mfy37wuzz {
  stop-color: var(--svg-color--8d8b8c, #8D8B8C);
}

.q3rp4efeb {
  d: path("M8.961 9.835c-1.293 0-1.447.728-1.362 1.093v14.405h22.393V15.059l-7.065-7.02H12.239c-1.063 1.048-1.661 1.796-3.278 1.796");
}

.r4c4wlbjv {
  stop-color: var(--svg-color--987469, #987469);
  stop-opacity: 0;
}

.rj6sl96xk {
  stop-color: var(--svg-color--9a9692, #9A9692);
  stop-opacity: 0;
}

.soq-7oghd {
  stop-color: var(--svg-color--bb8672, #BB8672);
}

.svnkaacda {
  stop-color: var(--svg-color--f8f7fd, #F8F7FD);
  stop-opacity: 0;
}

.t4nv07b4q {
  stop-color: var(--svg-color--7c5b51, #7C5B51);
}

.wjheywb8l {
  d: path("M16.045 9.803c-1.548 0-2.756-.548-4.257-1.312c.654-.654 2.256-2.258 3.426-3.436c1.463-1.472 3.426-1.34 4.738 0a308 308 0 0 0 3.256 3.257c-.103-.032-.494-.095-1.227-.095c-.915 0-1.972.35-2.576.67s-1.812.916-3.36.916");
}

.wrn2o0bzh {
  stop-color: var(--svg-color--42b671, #42B671);
}

.x72912byk {
  stop-color: var(--svg-color--f8f7fd, #F8F7FD);
}

.z-yl_xytl {
  stop-color: var(--svg-color--9a9692, #9A9692);
}

.zc4x5xyel {
  stop-color: var(--svg-color--ba7b67, #BA7B67);
}

</style>
