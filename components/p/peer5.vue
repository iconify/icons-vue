<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":291};
const content = `<g class="bi12bsetm"><path class="dse4lm8fh"/><path class="eziwbz95s"/><path class="shy16hbqe"/><path class="t-oqsjbzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:peer5" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.dse4lm8fh {
  fill: var(--svg-color--e44d26, #e44d26);
  d: path("m0 0l23.297 261.31l104.546 29.022l104.835-29.064L256 0z");
}

.eziwbz95s {
  fill: var(--svg-color--ef6429, #ef6429);
  d: path("m128 268.117l84.712-23.485l19.93-223.266H128z");
}

.shy16hbqe {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M80.798 84.426H128l1.001-1.364V54.505L128 52.412H47.481L60.82 232.368l31.043 9.216l-5.092-78.336H128l1.001-1.425v-28.467L128 131.234H83.678z");
}

.t-oqsjbzm {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M128 52.412h75.184l-8.003 110.835H128v-32.013h36.652l3.366-46.808H128z");
}

</style>
