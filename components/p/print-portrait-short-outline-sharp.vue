<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b65hm9akh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-short-outline-sharp" /></template>
<style>
.b65hm9akh {
  fill: currentColor;
  d: path("M6.752 5h10.229zM3.994 15.192h9.693q1.298-2.396 2.228-4.937T16.98 5H6.752q-.068 2.683-.885 5.209t-1.873 4.983m-.698 1l-.525-.667q1.221-2.761 2.062-5.632T5.752 4h1.877V3H9.32v1h5.102V3h1.693v1h1.096l.769.77q-.148 3.051-1.185 5.894q-1.036 2.842-2.484 5.528zM5.764 20v-4.308h1V19H16.98V4.77h1V20z");
}

</style>
