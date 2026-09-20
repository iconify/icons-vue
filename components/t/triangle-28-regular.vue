<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jzxvft0uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-28-regular" /></template>
<style>
.jzxvft0uc {
  fill: currentColor;
  d: path("M12.034 4.158c.857-1.542 3.076-1.542 3.933 0l8.965 16.127c.926 1.667-.279 3.715-2.185 3.715H5.254c-1.907 0-3.112-2.048-2.185-3.715zm2.622.729a.75.75 0 0 0-1.311 0L4.38 21.014a1 1 0 0 0 .874 1.486h17.493a1 1 0 0 0 .874-1.486z");
}

</style>
