<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma-jhabth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moon" /></template>
<style>
.ma-jhabth {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.721 14.705q-1.447 5.092-6.571 6.424q-5.124 1.331-8.867-2.412T2.871 9.85t6.424-6.571q.143-.041.292-.024q.148.017.278.09t.223.189t.133.261q.028.096.029.196q.001.101-.024.198q-.025.096-.075.183t-.12.158Q8.077 6.485 8.077 9.249q.001 2.764 1.955 4.719q1.955 1.954 4.719 1.955q2.764 0 4.719-1.954q.052-.052.114-.093q.061-.041.129-.069t.141-.043t.146-.014t.147.014q.072.015.14.043t.13.07q.061.041.114.093q.07.071.12.158t.075.183t.024.198q-.001.1-.029.196");
}

</style>
