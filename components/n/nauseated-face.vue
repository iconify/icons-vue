<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="crwevnb6q"/><g class="ehflfu9wl"><circle class="g5u0see7s"/><circle class="v2m15vb_h"/><path class="r04lj3b9y"/><path class="hguja2bbc"/></g><path class="k5n5ctbzz"/><g class="aiyllabmy"><path class="ooi-uzf1u"/><circle class="x7mze_y6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:nauseated-face" /></template>
<style>
.aiyllabmy {
  fill: var(--svg-color--ff717f, #ff717f);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.crwevnb6q {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--c7e755, #c7e755);
}

.ehflfu9wl {
  fill: var(--svg-color--425e21, #425e21);
}

.g5u0see7s {
  cx: 20.5px;
  cy: 27px;
  r: 4.5px;
}

.hguja2bbc {
  d: path("M23.7 35c1 2 1.6 4.4 1.6 7s-.6 5-1.6 7c2.1-.9 3.6-3.7 3.6-7s-1.5-6.1-3.6-7m16.6 14c-1-2-1.6-4.4-1.6-7s.6-5 1.6-7c-2.1.9-3.6 3.7-3.6 7s1.5 6 3.6 7");
}

.k5n5ctbzz {
  fill: var(--svg-color--75a843, #75a843);
  d: path("M25.6 15.9c-3.2 2.7-7.5 3.9-11.7 3.1c-.6-.1-1.1 2-.4 2.2c4.8.9 9.8-.5 13.5-3.6c.5-.5-1-2.1-1.4-1.7m24.5 3c-4.2.7-8.5-.4-11.7-3.1c-.4-.4-2 1.2-1.4 1.7c3.7 3.2 8.7 4.5 13.5 3.6c.7-.2.2-2.3-.4-2.2");
}

.ooi-uzf1u {
  d: path("M51.7 30.3c4.9 0 8.8 4 8.8 8.8c0 4.9-4 8.8-8.8 8.8c-4.9 0-8.8-4-8.8-8.8c-.1-4.8 3.9-8.8 8.8-8.8");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.r04lj3b9y {
  d: path("M37.4 43.2H26.6c-.7 0-.7-2.5 0-2.5h10.7c.8 0 .8 2.5.1 2.5");
}

.v2m15vb_h {
  cx: 43.5px;
  cy: 27px;
  r: 4.5px;
}

.x7mze_y6r {
  cx: 12.3px;
  cy: 39.1px;
  r: 8.8px;
  opacity: var(--svg-opacity--0-8, 0.8);
}

</style>
