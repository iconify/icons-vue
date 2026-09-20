<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyl-ar1pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nightlife-outline-sharp" /></template>
<style>
.pyl-ar1pc {
  fill: currentColor;
  d: path("M5 20v-2h2v-4L1 5h14l-6 9v4h2v2zm.9-11h4.2l1.4-2h-7zm7.975 10.125Q13 18.25 13 17t.875-2.125T16 14q.275 0 .525.038T17 14.2V5h5v3h-3v9q0 1.25-.875 2.125T16 20t-2.125-.875");
}

</style>
