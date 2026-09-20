<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vo-46_0kw"/><path class="ju1np5szn"/><path class="vc0je413f"/><path class="grak3vblq"/><circle class="r7cjibb2o"/><circle class="gvus1_byq"/><circle class="rh0m0lm3b"/><circle class="oh0wsubyi"/><path class="vun0-0xzj"/><path class="z8isv9bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:minibus" /></template>
<style>
.grak3vblq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M5.686 26h6.629c-.95-.631-2.088-1-3.314-1a5.96 5.96 0 0 0-3.315 1m18.001 0h6.629c-.949-.632-2.089-1-3.315-1s-2.364.369-3.314 1");
}

.gvus1_byq {
  cx: 9px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.ju1np5szn {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M0 23h36v3H0z");
}

.oh0wsubyi {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.r7cjibb2o {
  cx: 9px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.rh0m0lm3b {
  cx: 27px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.vc0je413f {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M9 25a5.997 5.997 0 0 0-5.993 5.861c.32.081.648.139.993.139h11a6 6 0 0 0-6-6m23.993 5.86A5.996 5.996 0 0 0 27 25c-3.312 0-6 2.687-6 6h11c.345 0 .674-.058.993-.14");
}

.vo-46_0kw {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M35 10c0-1-1-4-4-4H9.401C6 6 0 18 0 21v6a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V17c0-1.027-1-7-1-7");
}

.vun0-0xzj {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M5 13h6v7H2zm8 0h8v7h-8zm10 0v7h13v-3c0-.526-.262-2.347-.518-4z");
}

.z8isv9bmb {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M33 11H7a1 1 0 0 1 0-2h26a1 1 0 1 1 0 2");
}

</style>
