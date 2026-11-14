<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr_us_8rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quote-marks" /></template>
<style>
.lr_us_8rw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 6q-4 0-4 4t4 4q1.074 0 1.86-.288q-1.112 2.794-4.155 4.099q-.138.058-.242.165t-.159.245q-.056.139-.054.288t.061.286q.029.068.071.129t.094.113q.053.051.115.092q.062.04.13.067q.069.028.142.041t.146.013q.074-.001.146-.016q.073-.016.14-.045Q11 16.745 11 10q0-4-4-4m9.5 0q-4 0-4 4t4 4q1.074 0 1.86-.288q-1.112 2.794-4.155 4.099q-.138.058-.242.165t-.159.245t-.054.288t.061.286q.029.068.071.129t.094.113q.053.051.115.092q.062.04.13.067q.069.028.142.041t.146.013q.074-.001.146-.016q.073-.016.14-.045Q20.5 16.745 20.5 10q0-4-4-4");
}

</style>
