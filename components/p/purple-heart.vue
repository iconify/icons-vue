<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZFX2Xp)" class="caio2cbjk"/><path fill="url(#ib4vQPe)" class="caio2cbjk"/><path fill="url(#iSRBmTc)" class="caio2cbjk"/><path fill="url(#i1brkKc)" class="caio2cbjk"/><path fill="url(#iKvCTlH)" class="caio2cbjk"/><path fill="url(#iRKXT3c)" class="caio2cbjk"/><path fill="url(#iQy85Sb)" class="caio2cbjk"/><path fill="url(#iMJ1Nac)" class="caio2cbjk"/><path fill="url(#i25MKvd)" class="fyqk7jbxh"/><g filter="url(#iiTW2wb)"><path fill="url(#i7e4uVd)" class="z_gxvxefy"/></g><g filter="url(#iuMd5sb)"><ellipse fill="url(#iTXkHib)" transform="rotate(-67.627 22.951 14.119)" class="xl4ycjb9i"/></g><g filter="url(#iE5Bfgd)"><path fill="url(#ioifxWb)" class="qgobm286e"/></g><g filter="url(#iFJ2jEb)"><path stroke="url(#i3fMAEb)" class="b43qmlb8s"/></g><g filter="url(#ivTlLwc)"><path fill="url(#i94eIWd)" class="aea4hzrcj"/></g><defs><radialGradient id="iZFX2Xp" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.8283 -29.4623 0 15.77 5.66)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="c1buc7ohe"/><stop offset=".528" class="vn_2pw88r"/><stop offset="1" class="s6s-8ibqd"/></radialGradient><radialGradient id="ib4vQPe" cx="0" cy="0" r="1" gradientTransform="rotate(-57.293 33.306 3.678)scale(30.305 28.3828)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="ijunbo2sg"/><stop offset="1" class="xkfp1mbow"/></radialGradient><radialGradient id="i1brkKc" cx="0" cy="0" r="1" gradientTransform="rotate(140.774 9.203 9.753)scale(19.7667 28.2971)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="fultbibis"/><stop offset="1" class="tns5d--dz"/></radialGradient><radialGradient id="iRKXT3c" cx="0" cy="0" r="1" gradientTransform="rotate(-154.781 12.676 5.033)scale(21.4163 18.6261)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="zxnc3ybji"/><stop offset="1" class="w37ncqt6a"/></radialGradient><radialGradient id="iQy85Sb" cx="0" cy="0" r="1" gradientTransform="rotate(-129.075 12.845 4.917)scale(18.839 27.0981)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="zxnc3ybji"/><stop offset="1" class="w37ncqt6a"/></radialGradient><radialGradient id="iMJ1Nac" cx="0" cy="0" r="1" gradientTransform="scale(20.0528 17.499)rotate(90 -.01 .78)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="max-rhuny"/><stop offset=".934" class="d1f6q0uqp"/></radialGradient><radialGradient id="i7e4uVd" cx="0" cy="0" r="1" gradientTransform="rotate(107.322 8.768 11.257)scale(13.2248 14.8114)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="d6v7scc3h"/><stop offset="1" class="fultbibis"/></radialGradient><radialGradient id="iTXkHib" cx="0" cy="0" r="1" gradientTransform="rotate(-173.542 16.852 6.761)scale(15.5528 7.3671)" gradientUnits="userSpaceOnUse"><stop class="t5f_h2nxe"/><stop offset="1" class="b78p8fb7l"/></radialGradient><radialGradient id="ioifxWb" cx="0" cy="0" r="1" gradientTransform="rotate(-134.829 11.368 3.888)scale(11.1704 7.39051)" gradientUnits="userSpaceOnUse"><stop class="t5f_h2nxe"/><stop offset="1" class="b78p8fb7l"/></radialGradient><linearGradient id="iSRBmTc" x1="17.632" x2="25.645" y1="16.159" y2="25.694" gradientUnits="userSpaceOnUse"><stop offset=".694" class="wqge7ob_z"/><stop offset=".934" class="qa0xd3bfv"/></linearGradient><linearGradient id="iKvCTlH" x1="16.639" x2="7.188" y1="16.556" y2="27.206" gradientUnits="userSpaceOnUse"><stop offset=".694" class="max-rhuny"/><stop offset=".885" class="d1f6q0uqp"/></linearGradient><linearGradient id="i25MKvd" x1="17.125" x2="18.887" y1="7.445" y2="8.863" gradientUnits="userSpaceOnUse"><stop class="vqqnf6bdd"/><stop offset=".68" class="hhrk2rbov"/></linearGradient><linearGradient id="i3fMAEb" x1="7.063" x2="13.563" y1="6.347" y2="6.988" gradientUnits="userSpaceOnUse"><stop class="k9bz-vbky"/><stop offset="1" class="jm4577b3k"/></linearGradient><linearGradient id="i94eIWd" x1="18.563" x2="10.563" y1="30.425" y2="16.675" gradientUnits="userSpaceOnUse"><stop class="mraii1qsb"/><stop offset="1" class="v8gv1mb0n"/></linearGradient><filter id="iiTW2wb" width="9.756" height="13.67" x="13.82" y="5.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6111" stdDeviation="1"/></filter><filter id="iuMd5sb" width="14.114" height="17.881" x="15.894" y="5.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6111" stdDeviation=".75"/></filter><filter id="iE5Bfgd" width="12.852" height="21.845" x="5.192" y="3.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6111" stdDeviation="1.5"/></filter><filter id="iFJ2jEb" width="8.649" height="5.715" x="7.316" y="5.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6111" stdDeviation=".5"/></filter><filter id="ivTlLwc" width="16" height="21.875" x="1.625" y="8.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6111" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:purple-heart" /></template>
<style>
.aea4hzrcj {
  d: path("M3.625 13.55c2.063 8.063 9.48 13.23 12 14.813c-2.9-5.25-5.562-15.542-5.625-17.875z");
}

.b43qmlb8s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.44 6.44c1.087-.136 4.025 0 6.4 3.432");
}

.b78p8fb7l {
  stop-color: var(--svg-color--c874ff, #C874FF);
  stop-opacity: 0;
}

.c1buc7ohe {
  stop-color: var(--svg-color--ac3bff, #AC3BFF);
}

.caio2cbjk {
  d: path("M15.104 29.227a1.73 1.73 0 0 0 1.71-.022c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.024-1.897 1.542c-.238.234-.657.258-.904.033c-.69-.628-1.771-1.435-2.465-1.904c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.11 12.475");
}

.d1f6q0uqp {
  stop-color: var(--svg-color--b694ff, #B694FF);
}

.d6v7scc3h {
  stop-color: var(--svg-color--8e26e9, #8E26E9);
}

.ft5dv1b6b {
  fill: none;
}

.fultbibis {
  stop-color: var(--svg-color--6721fd, #6721FD);
  stop-opacity: 0;
}

.fyqk7jbxh {
  d: path("m15.219 7.832l.347.318c.954.873 2.499.63 3.365-.33c.913-1.014 2.14-2.064 3.624-2.792c-1.403.03-2.841.507-4.148 1.534l-.475.367c-.497.38-1.027.785-1.422 1.174c-.238.234-.657.258-.904.034q-.18-.164-.389-.34z");
}

.hhrk2rbov {
  stop-color: var(--svg-color--7241ad, #7241AD);
  stop-opacity: 0;
}

.ijunbo2sg {
  stop-color: var(--svg-color--b350ff, #B350FF);
  stop-opacity: 0;
}

.jm4577b3k {
  stop-color: var(--svg-color--b659ff, #B659FF);
  stop-opacity: 0;
}

.k9bz-vbky {
  stop-color: var(--svg-color--c274ff, #C274FF);
}

.max-rhuny {
  stop-color: var(--svg-color--9f72ff, #9F72FF);
  stop-opacity: 0;
}

.mraii1qsb {
  stop-color: var(--svg-color--7c22fd, #7C22FD);
}

.qa0xd3bfv {
  stop-color: var(--svg-color--9f72ff, #9F72FF);
}

.qgobm286e {
  d: path("m14.84 9.207l.205 13.406C8.17 15.926 6.939 8.76 9.277 7.153c1.67-1.147 4.813.491 5.563 2.054");
}

.s6s-8ibqd {
  stop-color: var(--svg-color--8c1eed, #8C1EED);
}

.t5f_h2nxe {
  stop-color: var(--svg-color--d28cff, #D28CFF);
}

.tns5d--dz {
  stop-color: var(--svg-color--7f21fd, #7F21FD);
}

.v8gv1mb0n {
  stop-color: var(--svg-color--7c22fd, #7C22FD);
  stop-opacity: 0;
}

.vn_2pw88r {
  stop-color: var(--svg-color--9d32ff, #9D32FF);
}

.vqqnf6bdd {
  stop-color: var(--svg-color--7241ad, #7241AD);
}

.w37ncqt6a {
  stop-color: var(--svg-color--773cac, #773CAC);
}

.wqge7ob_z {
  stop-color: var(--svg-color--b694ff, #B694FF);
  stop-opacity: 0;
}

.xkfp1mbow {
  stop-color: var(--svg-color--b350ff, #B350FF);
}

.xl4ycjb9i {
  cx: 22.951px;
  cy: 14.119px;
  rx: 7.767px;
  ry: 5.087px;
}

.z_gxvxefy {
  d: path("m15.821 10.242l.38 6.26c.062 1.035 1.577 1.358 2.114.472c2.329-3.838 4.441-6.39 2.497-8.673c-.82-.964-2.987-.443-4.713 1.205a.93.93 0 0 0-.278.736");
}

.zxnc3ybji {
  stop-color: var(--svg-color--773cac, #773CAC);
  stop-opacity: 0;
}

</style>
