<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG91oNhb0B)" class="iqs0lv26y"/><path fill="url(#SVGCAZ0XV4K)" class="th33qacxc"/><path fill="url(#SVGNGwrBU1l)" class="wj651laal"/><path fill="url(#SVGTUUb1Ozm)" class="lcewnibpy"/><path fill="url(#SVGQXUwAx3M)" class="z84t_olle"/><path fill="url(#SVGxmgPAeCO)" class="ov4c45b1h"/><defs><linearGradient id="SVG91oNhb0B" x1="6.994" x2="13.804" y1="4.511" y2="23.644" gradientUnits="userSpaceOnUse"><stop offset=".02" class="p9px83imy"/><stop offset=".54" class="uexu2qbpz"/></linearGradient><linearGradient id="SVGCAZ0XV4K" x1="6.994" x2="14.063" y1="2.999" y2="17.889" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p9px83imy"/><stop offset=".79" class="uexu2qbpz"/></linearGradient><linearGradient id="SVGNGwrBU1l" x1="6.994" x2="13.804" y1="4.512" y2="23.645" gradientUnits="userSpaceOnUse"><stop offset=".52" class="uexu2qbpz"/><stop offset=".86" class="p9px83imy"/></linearGradient><linearGradient id="SVGTUUb1Ozm" x1="6.995" x2="14.064" y1="3" y2="17.889" gradientUnits="userSpaceOnUse"><stop offset=".52" class="uexu2qbpz"/><stop offset=".86" class="p9px83imy"/></linearGradient><linearGradient id="SVGQXUwAx3M" x1="16.435" x2="4.156" y1="4.013" y2="16.862" gradientUnits="userSpaceOnUse"><stop offset=".05" class="x-f-1vb7i"/><stop offset=".26" class="tknx7419l"/><stop offset=".76" class="jf5vw4b7n"/></linearGradient><linearGradient id="SVGxmgPAeCO" x1="13.384" x2="10.029" y1="9.015" y2="14.625" gradientUnits="userSpaceOnUse"><stop offset=".06" class="i49p1ioky"/><stop offset=".8" class="gyi-mdbqg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pzp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gyi-mdbqg {
  stop-color: var(--svg-color--f3f14f, #f3f14f);
}

.i49p1ioky {
  stop-color: var(--svg-color--f96428, #f96428);
}

.iqs0lv26y {
  d: path("M11.5 18.5h1v1.945c0 .305-.225.555-.5.555s-.5-.25-.5-.555z");
}

.jf5vw4b7n {
  stop-color: var(--svg-color--ffab39, #ffab39);
}

.lcewnibpy {
  d: path("M14.5 6h-.999V4.055c0-.305.225-.555.5-.555s.5.25.5.555z");
}

.ov4c45b1h {
  d: path("m12.53 8.95l-1.415 2.45c-.26.445-.615.93-.615 1.35c0 1 .695 1.565 1 1.75c.585-.825.805-1.155 1.375-1.995a3.28 3.28 0 0 0 .625-2.175c0-1.495-1.385-2.286-2-2.33H9.055A2.25 2.25 0 0 1 7 6.523C7 7.744 8.015 8.5 9.27 8.5h2.23c.385 0 .75.25 1.03.45");
}

.p9px83imy {
  stop-color: var(--svg-color--d4964b, #d4964b);
}

.th33qacxc {
  d: path("M9.5 17.5h1v1.945c0 .305-.225.555-.5.555c-.276 0-.5-.25-.5-.555z");
}

.tknx7419l {
  stop-color: var(--svg-color--fce34b, #fce34b);
}

.uexu2qbpz {
  stop-color: var(--svg-color--ffed87, #ffed87);
}

.wj651laal {
  d: path("M12.5 5.5h-1V3.555c0-.305.225-.555.5-.555s.5.25.5.555z");
}

.x-f-1vb7i {
  stop-color: var(--svg-color--f8fcda, #f8fcda);
}

.z84t_olle {
  d: path("M7 5v1.525C7 7.745 8.015 8.5 9.27 8.5h2.125c.455 0 .9.14 1.065.21a328 328 0 0 0-3.9 4.115c-.365.42-1.56 1.7-1.56 3.32A2.22 2.22 0 0 0 8.915 18.5h8.086v-1.525C17 15.755 15.984 15 14.73 15h-1.98a4.7 4.7 0 0 1-1.246-.21c1.015-1.06 3.275-3.53 3.725-3.975c.57-.55 1.775-1.59 1.775-3.53c0-1.55-1.18-2.17-1.775-2.285z");
}

</style>
