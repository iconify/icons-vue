<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5512xbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tnt" /></template>
<style>
.r5512xbst {
  fill: var(--svg-color--f94081, #f94081);
  d: path("M15.937 14.125a53 53 0 0 0-7.875 0l-.264-3.487a57 57 0 0 1 8.404 0zm-2.25 5.468a28 28 0 0 0-3.374 0c-.034-1.193-.09-1.62-.124-2.813c1.44-.073 2.16-.067 3.6 0zM3 5.187l.58 4.078c.337-.596.506-.9.854-1.485a51.2 51.2 0 0 1 15.311.028c.282.58.411.872.675 1.457c.226-1.63.344-2.447.58-4.078a52.3 52.3 0 0 0-18 0");
}

</style>
