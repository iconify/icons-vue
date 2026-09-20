<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zoa7y9b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-checkmark-28-filled" /></template>
<style>
.zoa7y9b5h {
  fill: currentColor;
  d: path("M6.75 3h6.5v10.25H3v-6.5A3.75 3.75 0 0 1 6.75 3M3 14.75h10.25V25h-6.5A3.75 3.75 0 0 1 3 21.25zm11.75 0V25h6.5A3.75 3.75 0 0 0 25 21.25v-6.5zm0-11.75v10.25H25v-6.5A3.75 3.75 0 0 0 21.25 3zm8.028 15.78l-3 3a.75.75 0 0 1-1.06 0l-1.498-1.498a.75.75 0 0 1 1.06-1.06l.968.967l2.47-2.47a.75.75 0 0 1 1.06 1.061");
}

</style>
