<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQZ88fb)"><path clip-rule="evenodd" class="m-08t_bhb"/></g><g filter="url(#iZVuVfd)"><path fill="url(#iHRPkZX)" class="q28olxe4d"/><path fill="url(#iM3Jgyd)" class="q28olxe4d"/></g><path fill="url(#iuTMbBb)" class="uw_fd3bfy"/><path fill="url(#iPIsboc)" class="uw_fd3bfy"/><path fill="url(#iLbdsRc)" class="uw_fd3bfy"/><path fill="url(#iLSMFgb)" class="uw_fd3bfy"/><path fill="url(#im4i8Dc)" class="uw_fd3bfy"/><rect transform="rotate(45 3.699 20.484)" class="o7g01114d"/><rect fill="url(#iaU6uBb)" transform="rotate(45 3.699 20.484)" class="zqj-3xx3w"/><rect fill="url(#iMFY1kd)" transform="rotate(45 3.699 20.484)" class="zqj-3xx3w"/><rect fill="url(#iDge5qb)" transform="rotate(45 3.699 20.484)" class="zqj-3xx3w"/><rect fill="url(#iq5aM6c)" transform="rotate(45 3.699 20.484)" class="zqj-3xx3w"/><defs><radialGradient id="iM3Jgyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14277 1.0916 -1.28303 -2.51853 16.883 25.145)" gradientUnits="userSpaceOnUse"><stop class="whvfbd4rf"/><stop offset="1" class="skzob7b5n"/></radialGradient><radialGradient id="iuTMbBb" cx="0" cy="0" r="1" gradientTransform="matrix(14.5 -9.125 3.43262 5.45458 10.12 25.25)" gradientUnits="userSpaceOnUse"><stop offset=".024" class="o1ihrlj8x"/><stop offset="1" class="r5zu607vv"/></radialGradient><radialGradient id="iLbdsRc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 1.56249 -6.34069 -7.10164 23.996 11.375)" gradientUnits="userSpaceOnUse"><stop class="knxl4ebbl"/><stop offset="1" class="k9d774bve"/></radialGradient><radialGradient id="iLSMFgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33379 1.18749 -5.26453 -5.91315 17.173 3.594)" gradientUnits="userSpaceOnUse"><stop class="yn7w57iyn"/><stop offset="1" class="voaw15bpl"/></radialGradient><radialGradient id="iaU6uBb" cx="0" cy="0" r="1" gradientTransform="rotate(-178.141 7.134 11.676)scale(7.49486 2.103)" gradientUnits="userSpaceOnUse"><stop class="icjrkjnkd"/><stop offset="1" class="t84knjb1t"/></radialGradient><radialGradient id="iDge5qb" cx="0" cy="0" r="1" gradientTransform="rotate(93.759 -5.207 15.157)scale(1.13768 3.75057)" gradientUnits="userSpaceOnUse"><stop class="l0wprux9d"/><stop offset="1" class="bdc1u6fnk"/></radialGradient><radialGradient id="iq5aM6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.17117 4.4415 -15.5696 4.10553 11.167 19.887)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="rj2byjh8s"/><stop offset=".94" class="buwfseb7j"/></radialGradient><linearGradient id="iHRPkZX" x1="25.375" x2="21.596" y1="23.689" y2="25.734" gradientUnits="userSpaceOnUse"><stop class="whvfbd4rf"/><stop offset="1" class="skzob7b5n"/></linearGradient><linearGradient id="iPIsboc" x1="5.746" x2="13.558" y1="14.25" y2="18.375" gradientUnits="userSpaceOnUse"><stop offset=".211" class="otbzo0eld"/><stop offset="1" class="arpczrb9t"/></linearGradient><linearGradient id="im4i8Dc" x1="20.746" x2="19.839" y1="22.875" y2="20.906" gradientUnits="userSpaceOnUse"><stop offset=".094" class="zmu2m1zjo"/><stop offset="1" class="q3u3n4n3w"/></linearGradient><linearGradient id="iMFY1kd" x1="6.152" x2="9.267" y1="24.152" y2="20.418" gradientUnits="userSpaceOnUse"><stop class="hvzqvnb4l"/><stop offset="1" class="t1-0ss3oh"/></linearGradient><filter id="iQZ88fb" width="12.737" height="11.965" x="13.049" y="17.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.6 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17893"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.54902 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17893" result="effect2_innerShadow_18_17893"/></filter><filter id="iZVuVfd" width="11.679" height="10.852" x="13.749" y="17.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17893" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:megaphone" /></template>
<style>
.arpczrb9t {
  stop-color: var(--svg-color--c59635, #C59635);
  stop-opacity: 0;
}

.bdc1u6fnk {
  stop-color: var(--svg-color--fbb950, #FBB950);
  stop-opacity: 0;
}

.buwfseb7j {
  stop-color: var(--svg-color--f67698, #F67698);
}

.ft5dv1b6b {
  fill: none;
}

.hvzqvnb4l {
  stop-color: var(--svg-color--a77850, #A77850);
}

.icjrkjnkd {
  stop-color: var(--svg-color--f79f6d, #F79F6D);
}

.k9d774bve {
  stop-color: var(--svg-color--f9a53e, #F9A53E);
  stop-opacity: 0;
}

.knxl4ebbl {
  stop-color: var(--svg-color--fcc071, #FCC071);
}

.l0wprux9d {
  stop-color: var(--svg-color--fcca73, #FCCA73);
}

.m-08t_bhb {
  fill: var(--svg-color--fbba59, #FBBA59);
  fill-rule: evenodd;
  d: path("m13.05 21.647l9.684-3.947l2.34 5.743a2.85 2.85 0 0 1-1.563 3.715l-4.406 1.796a2.85 2.85 0 0 1-3.715-1.564zm2.476 1.043l1.623 3.983a.95.95 0 0 0 1.239.521l4.406-1.795a.95.95 0 0 0 .521-1.239l-1.623-3.983z");
}

.o1ihrlj8x {
  stop-color: var(--svg-color--fab66e, #FAB66E);
}

.o7g01114d {
  width: 10.927px;
  height: 3.315px;
  x: 3.699px;
  y: 20.484px;
  fill: var(--svg-color--faa72c, #FAA72C);
  rx: 1.657px;
}

.otbzo0eld {
  stop-color: var(--svg-color--a47f53, #A47F53);
}

.q28olxe4d {
  d: path("m14.576 21.934l-.094-.231l-.233.094l.095.232zm7.968-3.23l.231-.094l-.094-.23l-.231.093zm-3.486 9.136l-.094-.232zm-2.49-1.042l.232-.095zm7.969-3.23l-.232.095zm-1.048 2.476l.093.232zm-8.82-3.878l7.969-3.23l-.188-.463l-7.968 3.23zm7.643-3.367l1.993 4.864l.463-.19l-1.993-4.863zm1.083 7.014l-4.43 1.796l.187.463l4.43-1.796zm-6.595.89l-1.993-4.863l-.463.19l1.993 4.863zm2.164.906a1.664 1.664 0 0 1-2.164-.906l-.463.19a2.164 2.164 0 0 0 2.815 1.179zm5.341-3.946a1.647 1.647 0 0 1-.91 2.15l.188.463a2.147 2.147 0 0 0 1.185-2.803z");
}

.q3u3n4n3w {
  stop-color: var(--svg-color--f8a35f, #F8A35F);
  stop-opacity: 0;
}

.r5zu607vv {
  stop-color: var(--svg-color--ec9547, #EC9547);
}

.rj2byjh8s {
  stop-color: var(--svg-color--e26977, #E26977);
  stop-opacity: 0;
}

.skzob7b5n {
  stop-color: var(--svg-color--ffea7b, #FFEA7B);
  stop-opacity: 0;
}

.t1-0ss3oh {
  stop-color: var(--svg-color--db8e2f, #DB8E2F);
  stop-opacity: 0;
}

.t84knjb1t {
  stop-color: var(--svg-color--f79f6d, #F79F6D);
  stop-opacity: 0;
}

.uw_fd3bfy {
  d: path("M12.75 3.742c.793-1.81 3.16-2.252 4.552-.85l11.689 11.783c1.386 1.398.936 3.751-.868 4.538L9.277 27.438l-4.735-4.953z");
}

.voaw15bpl {
  stop-color: var(--svg-color--f29e36, #F29E36);
  stop-opacity: 0;
}

.whvfbd4rf {
  stop-color: var(--svg-color--ffea7b, #FFEA7B);
}

.yn7w57iyn {
  stop-color: var(--svg-color--eba659, #EBA659);
}

.zmu2m1zjo {
  stop-color: var(--svg-color--ec7e85, #EC7E85);
}

.zqj-3xx3w {
  width: 10.927px;
  height: 3.315px;
  x: 3.699px;
  y: 20.484px;
  rx: 1.657px;
}

</style>
