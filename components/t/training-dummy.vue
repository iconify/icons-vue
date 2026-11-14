<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h43gcf24o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:training-dummy" /></template>
<style>
.h43gcf24o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.5Q6.75 2.5 6.75 5v3.79Q3.938 9.112 3.938 12t2.812 3.21v4.29Q6.75 22 12 22t5.25-2.5v-4.29q2.813-.322 2.813-3.21T17.25 8.79V5q0-2.5-5.25-2.5m3.75 4.458V19.5q0 1-3.75 1t-3.75-1V6.958Q9.556 7.5 12 7.5t3.75-.542m-9 6.72Q5.438 13.396 5.438 12t1.312-1.678zM18.563 12q0 1.396-1.313 1.678v-3.356q1.313.282 1.313 1.678");
}

</style>
