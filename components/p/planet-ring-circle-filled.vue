<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGrzuJlrgw"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="rqdbkuvmp"/><path class="ib4veg3dm"/></g></mask></defs><circle mask="url(#SVGrzuJlrgw)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:planet-ring-circle-filled" /></template>
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

.ib4veg3dm {
  d: path("M5.888 17.326c.012-.09.055-.27.208-.573c.285-.563.83-1.296 1.628-2.137l-1.45-1.378c-.863.909-1.553 1.803-1.962 2.613c-.367.724-.697 1.765-.108 2.626c.513.75 1.411.894 2.113.876c.754-.019 1.643-.225 2.585-.55c1.897-.655 4.237-1.872 6.591-3.481c2.37-1.62 4.219-3.368 5.377-4.914c.575-.768 1.011-1.53 1.237-2.233c.216-.674.302-1.51-.172-2.203c-.332-.486-.83-.677-1.279-.723c-.418-.043-.856.03-1.254.128c-.732.182-1.634.538-2.572.907l-.244.096l.732 1.861l.188-.073c1-.394 1.782-.701 2.379-.85q.251-.061.391-.074a1.7 1.7 0 0 1-.074.32c-.133.415-.432.975-.933 1.645c-.997 1.332-2.67 2.934-4.905 4.462c-2.25 1.538-4.43 2.66-6.115 3.241c-.85.294-1.518.43-1.982.442a1.5 1.5 0 0 1-.379-.028");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.rqdbkuvmp {
  d: path("M13.476 7.423a5.476 5.476 0 1 0 0 10.952a5.476 5.476 0 0 0 0-10.952M6 12.9a7.476 7.476 0 1 1 14.951 0A7.476 7.476 0 0 1 6 12.9");
}

</style>
