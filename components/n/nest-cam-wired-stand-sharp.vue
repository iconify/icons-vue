<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_16_j2qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-cam-wired-stand-sharp" /></template>
<style>
.r_16_j2qy {
  fill: currentColor;
  d: path("M17 23H7v-3q0-2.1 1.463-3.55T12 15q.275 0 .525.025t.5.075l.55-.85l-1.85-.175q-2.425-.25-4.075-2.062T6 7.75q0-2.475 1.638-4.288T11.724 1.4l6.3-.6v13.875l-2.175-.2h-.025l-.95 1.425q.975.675 1.55 1.75T17 20z");
}

</style>
