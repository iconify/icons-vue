<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zdk112b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stove-20-regular" /></template>
<style>
.zdk112b4u {
  fill: currentColor;
  d: path("M13.5 15a1.5 1.5 0 0 1 0 3h-7a1.5 1.5 0 0 1 0-3zm-7 1a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm11-9a1.5 1.5 0 0 1 0 3H15v1a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V8.5A1.5 1.5 0 0 1 6.5 7zm-11 1a.5.5 0 0 0-.5.5V11a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V8.5a.5.5 0 0 0-.5-.5zm8.413 0q.085.236.087.5V9h2.5a.5.5 0 0 0 0-1zM5.5 2a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03C7.314 3.985 8 4.498 8 5.5a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C5.686 4.015 5 3.502 5 2.5a.5.5 0 0 1 .5-.5m3 0a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03c.474.355 1.16.868 1.16 1.87a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C8.686 4.015 8 3.502 8 2.5a.5.5 0 0 1 .5-.5m3 0a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03c.474.355 1.16.868 1.16 1.87a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C11.686 4.015 11 3.502 11 2.5a.5.5 0 0 1 .5-.5");
}

</style>
