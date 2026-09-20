<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb5ufabnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermometer-alert" /></template>
<style>
.eb5ufabnd {
  fill: currentColor;
  d: path("M16.98 11.02q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21M17 8V4h1v4zM8.77 20q-1.672 0-2.836-1.164Q4.769 17.67 4.769 16q0-1.084.544-1.987t1.456-1.475V6q0-.846.577-1.423T8.77 4t1.423.577T10.77 6v6.539q.912.57 1.446 1.474q.535.903.554 1.987q-.019 1.671-1.184 2.836Q10.422 20 8.77 20m-1-10h2V6q0-.425-.287-.712T8.769 5t-.712.288T7.769 6z");
}

</style>
