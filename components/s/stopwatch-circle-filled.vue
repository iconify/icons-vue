<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGDgjXkcOh"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="bcardtbka"/><path class="knbah-61p"/><path class="vp521dbxi"/></g></mask></defs><circle mask="url(#SVGDgjXkcOh)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:stopwatch-circle-filled" /></template>
<style>
.bcardtbka {
  d: path("M13 8.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11M5.5 14a7.5 7.5 0 1 1 15 0a7.5 7.5 0 0 1-15 0");
}

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

.knbah-61p {
  d: path("M5.793 6.793a1 1 0 0 1 1.414 0l1.5 1.5a1 1 0 0 1-1.414 1.414l-1.5-1.5a1 1 0 0 1 0-1.414m11.5 2.914a1 1 0 0 0 1.414 0l1.5-1.5a1 1 0 0 0-1.414-1.414l-1.5 1.5a1 1 0 0 0 0 1.414m-1.013 1.668a1 1 0 0 1-.155 1.406l-2.5 2a1 1 0 0 1-1.25-1.562l2.5-2a1 1 0 0 1 1.406.156M12 7V5h2v2z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.vp521dbxi {
  d: path("M10.5 5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

</style>
