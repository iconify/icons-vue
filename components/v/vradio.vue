<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4_pcgblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vradio" /></template>
<style>
.z4_pcgblj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.804h3.786l8.738 24.392m7.315-20.422l-7.315 20.422m18.45-20.422l-7.315 20.422m8.597-24.392H25.762m13.907 0c3.313 0 4.439 4.247 3.526 7.135c-.905 2.864-2.846 5.874-7.41 6.117l4.223 11.14");
}

</style>
