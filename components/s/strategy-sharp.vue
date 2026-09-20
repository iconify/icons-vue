<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay6filvvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:strategy-sharp" /></template>
<style>
.ay6filvvo {
  fill: currentColor;
  d: path("M13.5 21L8 17.788v-6.422l2.73-1.589v6.492h5.54V9.777L19 11.366v6.423zM6 10.846L3 9.135V5.712L6 4l3 1.712v3.423zM13 14V3h8l-1.654 2.5L21 8h-7v6z");
}

</style>
