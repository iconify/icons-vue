<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unu1_7_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermometer-alert-outline" /></template>
<style>
.unu1_7_nz {
  fill: currentColor;
  d: path("M8.764 20q-1.658 0-2.826-1.164Q4.768 17.67 4.768 16q0-1.084.544-1.987t1.456-1.475V6q0-.846.577-1.423T8.77 4t1.423.577T10.77 6v6.539q.912.57 1.446 1.474q.535.903.554 1.987q-.019 1.671-1.184 2.836Q10.422 20 8.764 20m.006-1q1.25 0 2.125-.875T11.77 16q0-.725-.312-1.35t-.888-1.05l-.8-.6V6q0-.425-.287-.712T8.769 5t-.712.288T7.769 6v7l-.8.6q-.575.425-.887 1.05T5.769 16q0 1.25.875 2.125T8.77 19m8.21-7.98q-.21-.209-.21-.52t.21-.52t.52-.21t.521.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21M17 8V4h1v4z");
}

</style>
