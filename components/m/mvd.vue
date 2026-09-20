<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG91tjtcAu)" class="e1ftlebsv"/><path fill="url(#SVGypet4ERW)" class="whgxsbu2f"/><path class="uizt4gmyk"/><path class="eu3fc_q7h"/><path fill="url(#SVGBpCIAcJj)" class="q0ezqgbpe"/><path fill="url(#SVG6gd0Tbyg)" class="qlq6lzbyt"/><path class="emmybzx8y"/><path class="cr6_auoqz"/><defs><linearGradient id="SVG91tjtcAu" x1="3" x2="12.98" y1="4.898" y2="24.985" gradientUnits="userSpaceOnUse"><stop class="piv-sbr_d"/><stop offset=".79" class="yk4s77bvh"/></linearGradient><linearGradient id="SVGypet4ERW" x1="6.532" x2="13.466" y1="14.205" y2="-.138" gradientUnits="userSpaceOnUse"><stop class="vf8nxsw7y"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGBpCIAcJj" x1="9.154" x2="12.601" y1="10.582" y2="15.596" gradientUnits="userSpaceOnUse"><stop class="jwj_s3usk"/><stop offset="1" class="ddbjr_bdv"/></linearGradient><linearGradient id="SVG6gd0Tbyg" x1="17.467" x2="10.534" y1="14.205" y2="-.138" gradientUnits="userSpaceOnUse"><stop class="vf8nxsw7y"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mvd" /></template>
<style>
.cr6_auoqz {
  fill: var(--svg-color--d28a1c, #d28a1c);
  d: path("m12 12l4.5-4.5V3L12 7.579z");
}

.ddbjr_bdv {
  stop-color: var(--svg-color--c77e0c, #c77e0c);
}

.e1ftlebsv {
  d: path("m3 7.5l9 9V21l-9-9z");
}

.emmybzx8y {
  fill: var(--svg-color--d79b3f, #d79b3f);
  d: path("M18.75 9.75L21 12V7.5z");
}

.eu3fc_q7h {
  fill: var(--svg-color--ffaa27, #ffaa27);
  d: path("M12 12L7.5 7.5V3L12 7.579z");
}

.ft5dv1b6b {
  fill: none;
}

.jwj_s3usk {
  stop-color: var(--svg-color--b06e07, #b06e07);
}

.piv-sbr_d {
  stop-color: var(--svg-color--955a00, #955a00);
}

.q0ezqgbpe {
  d: path("m21 7.5l-9 9V21l9-9z");
}

.qlq6lzbyt {
  d: path("m21 12l-4.5-4.5V3L21 7.5z");
}

.uizt4gmyk {
  fill: var(--svg-color--c58f3c, #c58f3c);
  d: path("M5.25 9.75L3 12V7.5z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vf8nxsw7y {
  stop-color: var(--svg-color--9e877a, #9e877a);
}

.whgxsbu2f {
  d: path("m3 12l4.5-4.5V3L3 7.5z");
}

.yk4s77bvh {
  stop-color: var(--svg-color--f29f20, #f29f20);
}

</style>
