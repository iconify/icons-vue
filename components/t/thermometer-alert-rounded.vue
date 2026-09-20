<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvayo0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermometer-alert-rounded" /></template>
<style>
.rvayo0bhf {
  fill: currentColor;
  d: path("M16.98 11.02q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.163-3.164Q17 7.713 17 7.5v-3q0-.213.144-.356T17.501 4t.356.144T18 4.5v3q0 .213-.144.356T17.499 8t-.356-.144M8.763 20q-1.657 0-2.825-1.164Q4.768 17.67 4.768 16q0-1.084.544-1.987t1.456-1.475V6q0-.846.577-1.423T8.77 4t1.423.577T10.77 6v6.539q.912.57 1.446 1.474q.535.903.554 1.987q-.019 1.671-1.184 2.836Q10.422 20 8.764 20M7.77 10h2V6q0-.425-.287-.712T8.769 5t-.712.288T7.769 6z");
}

</style>
