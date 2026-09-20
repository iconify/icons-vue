<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bb99zdcxa"/><path class="kjl088ivl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ooki" /></template>
<style>
.bb99zdcxa {
  fill: var(--svg-color--f6be4e, #f6be4e);
  fill-rule: evenodd;
  d: path("M15.478 20.098a8.7 8.7 0 0 1-3.396.598A8.7 8.7 0 0 1 3.7 15.417a8.707 8.707 0 0 1 8.383-12.115a8.7 8.7 0 0 1 3.396 16.796m-6.277-8.244a.544.544 0 1 1-.77-.77a.544.544 0 0 1 .77.77m6.533 0a.544.544 0 1 1-.77-.77a.544.544 0 0 1 .77.77m-4.48.458c.011-.168.12-.288.284-.299h1.094c.114 0 .25.109.272.234a.66.66 0 0 1-.049.354a.74.74 0 0 1-.196.3a.8.8 0 0 1-.566.2a.95.95 0 0 1-.599-.206a.74.74 0 0 1-.24-.583");
}

.ft5dv1b6b {
  fill: none;
}

.kjl088ivl {
  fill: var(--svg-color--e38329, #e38329);
  d: path("M20.696 10.673c1.1 4.094-1.786 8.477-6.387 9.707c-4.594 1.23-9.287-1.127-10.382-5.226c2.156 2.613 5.88 3.745 9.462 2.89c3.779-.898 6.708-3.849 7.307-7.371");
  opacity: var(--svg-opacity--0-69, 0.69);
}

</style>
