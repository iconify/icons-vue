<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc1-6fs9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:takeout-dining-2" /></template>
<style>
.mc1-6fs9h {
  fill: currentColor;
  d: path("M4.116 21L7.8 6.135l-.05-.7q-.044-.599-.421-1.017T6.369 4t-.976.398T5 5.385v1.442H4V5.384q0-.993.696-1.689T6.385 3h10.377q.946 0 1.626.647q.68.646.739 1.601L20 21zm1.33-1h3.21L8.008 9.439zM13 17.23h1.173v-3.826q.496-.131.835-.552q.338-.42.338-.969v-3.19h-.786v2.967h-.589V8.692h-.786v2.967h-.589V8.692h-.769v3.191q0 .548.329.97q.328.42.844.55z");
}

</style>
