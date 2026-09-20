<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv8gn5ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermometer-add-outline-rounded" /></template>
<style>
.qsv8gn5ue {
  fill: currentColor;
  d: path("M16.923 7.5h-2.5q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h2.5V4q0-.213.144-.356t.357-.144t.356.144t.143.356v2.5h2.5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-2.5V10q0 .213-.144.356q-.144.144-.357.144t-.356-.144t-.143-.356zM8.761 20q-1.663 0-2.827-1.164Q4.769 17.67 4.769 16q0-1.084.544-1.987t1.456-1.475V6q0-.846.577-1.423T8.77 4t1.423.577T10.77 6v6.539q.912.57 1.456 1.474T12.769 16q0 1.671-1.172 2.836T8.761 20M7.77 10h2V6q0-.425-.287-.712T8.769 5t-.712.288T7.769 6z");
}

</style>
