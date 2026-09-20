<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpdzaub6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-add-24-filled" /></template>
<style>
.zpdzaub6d {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M11.75 1.997a3.753 3.753 0 0 1 .75 7.43V11.5h2.497a6.5 6.5 0 0 0-2.185 1.5H7.75a.75.75 0 0 0-.75.75v.824a3.753 3.753 0 1 1-1.5.001v-.825a2.25 2.25 0 0 1 2.25-2.25H11V9.427a3.753 3.753 0 0 1 .75-7.43M17.5 14a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5");
}

</style>
