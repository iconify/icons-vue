<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGZy9Q1XxY"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="rkfoal7jx"/><path class="dzsj3bckl"/><path clip-rule="evenodd" class="mht3gqaaq"/></g></mask></defs><circle mask="url(#SVGZy9Q1XxY)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:taxi-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.dzsj3bckl {
  d: path("M19.5 16a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-10 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M7 18.5A1.5 1.5 0 0 1 8.5 20v1a1.5 1.5 0 0 1-3 0v-1A1.5 1.5 0 0 1 7 18.5m12 0a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-3 0v-1a1.5 1.5 0 0 1 1.5-1.5M13 4a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.mht3gqaaq {
  fill-rule: evenodd;
  d: path("M17.15 10.08a2 2 0 0 0-1.955-1.58h-4.39a2 2 0 0 0-1.956 1.58l-.429 2a2 2 0 0 0 1.956 2.42h5.248a2 2 0 0 0 1.955-2.42zm-1.526 2.42h-5.248l.429-2h4.39z");
}

.rkfoal7jx {
  fill-rule: evenodd;
  d: path("M9.171 6a2.5 2.5 0 0 0-2.425 1.894l-1.06 4.242A2.5 2.5 0 0 0 4 14.5v3A2.5 2.5 0 0 0 6.5 20h13a2.5 2.5 0 0 0 2.5-2.5v-3a2.5 2.5 0 0 0-1.685-2.364l-1.06-4.242A2.5 2.5 0 0 0 16.828 6zM6.5 14a1 1 0 0 0 .97-.758L8.686 8.38A.5.5 0 0 1 9.171 8h7.658a.5.5 0 0 1 .485.379l1.216 4.864a1 1 0 0 0 .97.757a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5");
}

</style>
