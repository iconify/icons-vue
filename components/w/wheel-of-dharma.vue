<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZSAtrd)"><rect fill="url(#iHdEvnd)" class="ovbsp8bsf"/><rect fill="url(#iuxJNPc)" class="ovbsp8bsf"/></g><g filter="url(#ieYbUyb)"><path stroke="url(#iDF7UFd)" class="cgak77bgt"/></g><g filter="url(#ixTne8p)"><path stroke="url(#iClFXNb)" class="uz6f_vb7s"/></g><g filter="url(#ituRrRc)"><path class="t1spi8byr"/></g><g filter="url(#iIwCsJj)"><path class="gdju1wbof"/></g><defs><filter id="iZSAtrd" width="29.875" height="28.875" x="1.723" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1025"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1025" result="effect2_innerShadow_18590_1025"/></filter><filter id="ieYbUyb" width="5.5" height="28.375" x="25.161" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1025" stdDeviation="1"/></filter><filter id="ixTne8p" width="27.281" height="5.5" x="2.437" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1025" stdDeviation="1"/></filter><filter id="ituRrRc" width="24.063" height="24.063" x="3.626" y="3.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1025" stdDeviation=".5"/></filter><filter id="iIwCsJj" width="22.863" height="22.863" x="4.226" y="4.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1025"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1025" result="effect2_innerShadow_18590_1025"/></filter><linearGradient id="iHdEvnd" x1="15.661" x2="15.661" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="iDF7UFd" x1="28.411" x2="28.411" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iClFXNb" x1="28.125" x2="2.593" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iuxJNPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.38 3.781)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wheel-of-dharma" /></template>
<style>
.cgak77bgt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.91 4.188v22.875");
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.gdju1wbof {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M15.657 4.594a.75.75 0 0 0-.75.75v.185a.1.1 0 0 1-.092.1A9.96 9.96 0 0 0 9.19 7.966a.1.1 0 0 1-.136-.005l-.136-.136a.75.75 0 0 0-1.061 1.06l.139.14A.1.1 0 0 1 8 9.16a9.96 9.96 0 0 0-2.311 5.622a.1.1 0 0 1-.1.093h-.214a.75.75 0 0 0 0 1.5h.219a.1.1 0 0 1 .1.092a9.96 9.96 0 0 0 2.335 5.594a.1.1 0 0 1-.006.136l-.167.168a.75.75 0 1 0 1.06 1.06l.17-.17a.1.1 0 0 1 .137-.005a9.96 9.96 0 0 0 5.59 2.309a.1.1 0 0 1 .093.1v.247a.75.75 0 1 0 1.5 0v-.247a.1.1 0 0 1 .093-.1a9.96 9.96 0 0 0 5.59-2.31a.1.1 0 0 1 .137.006l.17.17a.75.75 0 0 0 1.06-1.06l-.167-.168a.1.1 0 0 1-.005-.136a9.96 9.96 0 0 0 2.335-5.594a.1.1 0 0 1 .1-.092h.219a.75.75 0 1 0 0-1.5h-.214a.1.1 0 0 1-.1-.093a9.96 9.96 0 0 0-2.312-5.622a.1.1 0 0 1 .006-.136l.139-.139a.75.75 0 0 0-1.061-1.06l-.136.136a.1.1 0 0 1-.137.005A9.96 9.96 0 0 0 16.5 5.63a.1.1 0 0 1-.093-.1v-.185a.75.75 0 0 0-.75-.75m5.39 4.427a.1.1 0 0 1 .007.147l-3.798 3.798a.1.1 0 0 1-.123.015a3 3 0 0 0-.65-.272a.1.1 0 0 1-.076-.098V7.236a.1.1 0 0 1 .109-.1a8.46 8.46 0 0 1 4.531 1.885m-2.756 5.135a.1.1 0 0 1 .017-.121l3.803-3.804a.1.1 0 0 1 .148.008a8.46 8.46 0 0 1 1.859 4.528a.1.1 0 0 1-.1.108H18.65a.1.1 0 0 1-.098-.076a3 3 0 0 0-.26-.643m-.006 3.037a.1.1 0 0 1-.015-.123q.166-.293.264-.621a.1.1 0 0 1 .097-.074h5.381a.1.1 0 0 1 .1.11a8.46 8.46 0 0 1-1.882 4.499a.1.1 0 0 1-.147.006zm-1.19 1.035a.1.1 0 0 1 .12.016l3.805 3.804a.1.1 0 0 1-.008.147a8.46 8.46 0 0 1-4.496 1.856a.1.1 0 0 1-.109-.099v-5.375c0-.046.031-.086.075-.098q.323-.092.613-.251m-2.996.016a.1.1 0 0 1 .121-.016q.289.159.612.25a.1.1 0 0 1 .075.099v5.375c0 .059-.05.105-.108.099a8.46 8.46 0 0 1-4.497-1.856a.1.1 0 0 1-.007-.147zm-1.054-1.174a.1.1 0 0 1-.016.122l-3.798 3.799a.1.1 0 0 1-.147-.007a8.46 8.46 0 0 1-1.88-4.5a.1.1 0 0 1 .098-.109h5.381c.046 0 .085.03.098.074q.098.328.264.62m-.038-3.035a.1.1 0 0 1 .016.121a3 3 0 0 0-.26.643a.1.1 0 0 1-.098.076H7.297a.1.1 0 0 1-.099-.108a8.46 8.46 0 0 1 1.859-4.528a.1.1 0 0 1 .147-.008zm1.174-1.054a.1.1 0 0 1-.123-.015l-3.797-3.798a.1.1 0 0 1 .006-.147A8.46 8.46 0 0 1 14.8 7.137a.1.1 0 0 1 .108.099v5.375a.1.1 0 0 1-.075.098q-.344.098-.65.272m2.976 2.613a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.ovbsp8bsf {
  width: 27.875px;
  height: 27.875px;
  x: 1.723px;
  y: 1.688px;
  rx: 3.6px;
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.t1spi8byr {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M15.657 4.594a.75.75 0 0 0-.75.75v.185a.1.1 0 0 1-.092.1A9.96 9.96 0 0 0 9.19 7.966a.1.1 0 0 1-.136-.005l-.136-.136a.75.75 0 0 0-1.061 1.06l.139.14A.1.1 0 0 1 8 9.16a9.96 9.96 0 0 0-2.311 5.622a.1.1 0 0 1-.1.093h-.214a.75.75 0 0 0 0 1.5h.219a.1.1 0 0 1 .1.092a9.96 9.96 0 0 0 2.335 5.594a.1.1 0 0 1-.006.136l-.167.168a.75.75 0 1 0 1.06 1.06l.17-.17a.1.1 0 0 1 .137-.005a9.96 9.96 0 0 0 5.59 2.309a.1.1 0 0 1 .093.1v.247a.75.75 0 1 0 1.5 0v-.247a.1.1 0 0 1 .093-.1a9.96 9.96 0 0 0 5.59-2.31a.1.1 0 0 1 .137.006l.17.17a.75.75 0 0 0 1.06-1.06l-.167-.168a.1.1 0 0 1-.005-.136a9.96 9.96 0 0 0 2.335-5.594a.1.1 0 0 1 .1-.092h.219a.75.75 0 1 0 0-1.5h-.214a.1.1 0 0 1-.1-.093a9.96 9.96 0 0 0-2.312-5.622a.1.1 0 0 1 .006-.136l.139-.139a.75.75 0 0 0-1.061-1.06l-.136.136a.1.1 0 0 1-.137.005A9.96 9.96 0 0 0 16.5 5.63a.1.1 0 0 1-.093-.1v-.185a.75.75 0 0 0-.75-.75m5.39 4.427a.1.1 0 0 1 .007.147l-3.798 3.798a.1.1 0 0 1-.123.015a3 3 0 0 0-.65-.272a.1.1 0 0 1-.076-.098V7.236a.1.1 0 0 1 .109-.1a8.46 8.46 0 0 1 4.531 1.885m-2.756 5.135a.1.1 0 0 1 .017-.121l3.803-3.804a.1.1 0 0 1 .148.008a8.46 8.46 0 0 1 1.859 4.528a.1.1 0 0 1-.1.108H18.65a.1.1 0 0 1-.098-.076a3 3 0 0 0-.26-.643m-.006 3.037a.1.1 0 0 1-.015-.123q.166-.293.264-.621a.1.1 0 0 1 .097-.074h5.381a.1.1 0 0 1 .1.11a8.46 8.46 0 0 1-1.882 4.499a.1.1 0 0 1-.147.006zm-1.19 1.035a.1.1 0 0 1 .12.016l3.805 3.804a.1.1 0 0 1-.008.147a8.46 8.46 0 0 1-4.496 1.856a.1.1 0 0 1-.109-.099v-5.375c0-.046.031-.086.075-.098q.323-.092.613-.251m-2.996.016a.1.1 0 0 1 .121-.016q.289.159.612.25a.1.1 0 0 1 .075.099v5.375c0 .059-.05.105-.108.099a8.46 8.46 0 0 1-4.497-1.856a.1.1 0 0 1-.007-.147zm-1.054-1.174a.1.1 0 0 1-.016.122l-3.798 3.799a.1.1 0 0 1-.147-.007a8.46 8.46 0 0 1-1.88-4.5a.1.1 0 0 1 .098-.109h5.381c.046 0 .085.03.098.074q.098.328.264.62m-.038-3.035a.1.1 0 0 1 .016.121a3 3 0 0 0-.26.643a.1.1 0 0 1-.098.076H7.297a.1.1 0 0 1-.099-.108a8.46 8.46 0 0 1 1.859-4.528a.1.1 0 0 1 .147-.008zm1.174-1.054a.1.1 0 0 1-.123-.015l-3.797-3.798a.1.1 0 0 1 .006-.147A8.46 8.46 0 0 1 14.8 7.137a.1.1 0 0 1 .108.099v5.375a.1.1 0 0 1-.075.098q-.344.098-.65.272m2.976 2.613a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.uz6f_vb7s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.187 3.5h21.781");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
