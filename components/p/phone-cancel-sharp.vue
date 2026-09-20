<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frn_k9_nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-cancel-sharp" /></template>
<style>
.frn_k9_nd {
  fill: currentColor;
  d: path("m15.112 9.596l-.708-.707l2.094-2.1l-2.094-2.075l.708-.714l2.1 2.1L19.287 4l.713.713l-2.08 2.076l2.08 2.1l-.713.707l-2.075-2.075zM19.2 20q-2.702 0-5.418-1.244t-5.005-3.533q-2.27-2.289-3.523-5.021Q4 7.469 4 4.8V4h4.439l.848 4.083l-2.696 2.51q.684 1.186 1.417 2.167t1.527 1.769q.802.84 1.808 1.57t2.296 1.44l2.611-2.708l3.75.756V20z");
}

</style>
