<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcafrxjha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phishing" /></template>
<style>
.kcafrxjha {
  fill: currentColor;
  d: path("M7.471 18.471Q6 16.942 6 14.788v-4.576l3.558 3.634l-.689.695L7 12.594v2.195q0 1.727 1.185 2.969Q9.369 19 11.077 19t2.892-1.242q1.185-1.242 1.185-2.97V11.46q-.804-.177-1.315-.825q-.512-.646-.512-1.481t.502-1.491t1.325-.834V3h1v3.829q.823.177 1.335.834T18 9.153q0 .836-.512 1.486t-1.334.82v3.33q0 2.153-1.471 3.682T11.077 20t-3.606-1.529");
}

</style>
