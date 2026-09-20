<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkrac6t5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:meal-lunch" /></template>
<style>
.tkrac6t5e {
  fill: currentColor;
  d: path("M2 13v-3h2v3zm7.375-2.225L7.25 8.65l1.4-1.4l2.125 2.125zM2 8V2h6v1q0 2.075-1.463 3.538T3 8zm8-4V2h3v2zM1 22v-2h2q-.025-.075-.038-.137t-.037-.138L2 16h12l-.925 3.725q-.025.075-.038.138T13 20h2.075l1.5-6h-4.25L12 10h10l-.825 10H23v2z");
}

</style>
