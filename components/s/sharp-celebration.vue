<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd35top_o"/><path class="f05vatboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-celebration" /></template>
<style>
.f05vatboo {
  fill: currentColor;
  d: path("m15.97 4.97l-4.5 4.5l1.06 1.06L18.07 5l-3.53-3.53l-1.06 1.06z");
}

.fd35top_o {
  fill: currentColor;
  d: path("m2 22l14-5l-9-9zm12.53-9.47L21 6.05l1.48 1.48l1.06-1.06L21 3.93l-7.53 7.53zM10.94 6L9.47 7.47l1.06 1.06l2.54-2.54l-2.54-2.53l-1.06 1.07zm8.03 3.97l-3.5 3.5l1.06 1.06L19 12.06l2.5 2.49l1.06-1.06z");
}

</style>
