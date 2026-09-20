<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-hk3pbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switches-outline-rounded" /></template>
<style>
.g-hk3pbhr {
  fill: currentColor;
  d: path("M7.385 16q-1.671 0-2.836-1.164Q3.384 13.67 3.384 12T4.55 9.165T7.384 8q1.126 0 2.037.55T10.846 10h7.77q.846 0 1.423.577q.576.577.576 1.423t-.577 1.423t-1.422.577h-7.77q-.513.9-1.425 1.45T7.385 16m3.861-3h7.37q.425 0 .712-.288t.288-.712t-.288-.712t-.712-.288h-7.37q.07.225.104.5t.035.5t-.035.5t-.104.5M9.51 14.125q.875-.875.875-2.125T9.51 9.875T7.385 9t-2.125.875T4.385 12t.875 2.125T7.385 15t2.125-.875");
}

</style>
