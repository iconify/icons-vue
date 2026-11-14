<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u77o9o8vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nunchaku-training" /></template>
<style>
.u77o9o8vv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.295 6.818Q8.25 7.181 8.25 9.5v9q0 2.75-2.75 2.75T2.75 18.5v-9q0-1.139.805-1.945q.538-.537 1.223-.716q.295-3.316 3.658-4.041q1.543-.333 2.801.352q1.065.579 1.518 1.681q1.766-.526 2.877 1.397l4.5 7.794q1.374 2.381-1.007 3.757q-2.381 1.374-3.757-1.007l-4.5-7.794q-1.229-2.129.544-3.454q-.254-.71-.891-1.057q-.77-.418-1.769-.203q-2.167.468-2.457 2.554");
}

</style>
