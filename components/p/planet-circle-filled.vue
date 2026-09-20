<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGF8lrbZxc"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="p8th6fd-x"/><path class="rn4f_tbhy"/><path class="yfh41ubra"/></g></mask></defs><circle mask="url(#SVGF8lrbZxc)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:planet-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.p8th6fd-x {
  d: path("M13 6a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-9 7a9 9 0 1 1 18 0a9 9 0 0 1-18 0");
}

.rn4f_tbhy {
  d: path("M19.806 7.93a1 1 0 0 1-.367 1.365c-.676.39-1.564.688-2.55.897a1 1 0 1 1-.415-1.956c.872-.185 1.537-.427 1.967-.674a1 1 0 0 1 1.365.367M6.392 8.1a1 1 0 0 1 1.342-.445c1.033.518 2.958.915 5.266.915a1 1 0 0 1 0 2c-2.462 0-4.739-.414-6.162-1.127A1 1 0 0 1 6.392 8.1m14.363 3.317a1 1 0 0 1-.458 1.338C18.699 13.538 15.91 14 12.867 14c-2.87 0-5.494-.41-7.116-1.102a1 1 0 1 1 .784-1.84c1.27.541 3.588.942 6.332.942c2.931 0 5.358-.457 6.55-1.04a1 1 0 0 1 1.338.457m0 3.429a1 1 0 0 1-.458 1.338c-.853.418-2.247.719-3.706.92a36 36 0 0 1-4.734.325a1 1 0 1 1 0-2a34 34 0 0 0 4.46-.306c1.445-.2 2.559-.47 3.1-.735a1 1 0 0 1 1.338.458m-15.532.169a1 1 0 0 1 1.312-.528c.439.187 1.02.363 1.723.512a1 1 0 1 1-.412 1.957c-.789-.167-1.502-.377-2.095-.63a1 1 0 0 1-.528-1.311");
}

.yfh41ubra {
  d: path("M9.857 16.286a.429.429 0 1 0 0 .857a.429.429 0 0 0 0-.857m-2.428.428a2.429 2.429 0 1 1 4.857 0a2.429 2.429 0 0 1-4.857 0");
}

</style>
