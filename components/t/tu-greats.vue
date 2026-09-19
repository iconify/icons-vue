<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo6l_flfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tu-greats" /></template>
<style>
.uo6l_flfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.95 18.37v11.37c0 3.951 3.775 5.481 6.54 5.475V18.37m4.993-5.585v13.349a9.06 9.06 0 0 0 9.043 9.081h1.892a9.06 9.06 0 0 0 9.082-9.042V17.7c0-2.41-1.662-4.915-6.279-4.915v12.643c0 2.071-1.61 3.74-3.61 3.74h-.239c-2 0-3.61-1.669-3.61-3.74V17.7c0-2.41-1.737-4.915-6.324-4.915m.044 5.472H9.976c-3.952 0-5.482-2.706-5.476-5.472h18.983");
}

</style>
