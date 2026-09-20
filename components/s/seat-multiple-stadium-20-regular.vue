<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lnaauukbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:seat-multiple-stadium-20-regular" /></template>
<style>
.lnaauukbj {
  fill: currentColor;
  d: path("M12.25 3A2.75 2.75 0 0 1 15 5.75V8a3 3 0 0 1 3 3v4a2 2 0 0 1-2 2h-2a2 2 0 0 1-1.5-.68c-.367.416-.902.68-1.5.68H9a2 2 0 0 1-1.5-.68c-.367.416-.902.68-1.5.68H4a2 2 0 0 1-2-2v-4a3 3 0 0 1 3-3V5.75a2.75 2.75 0 0 1 5-1.578A2.75 2.75 0 0 1 12.25 3M4 14a1 1 0 1 0 0 2h2a1 1 0 1 0 0-2zm5 0a1 1 0 1 0 0 2h2a1 1 0 1 0 0-2zm5 0a1 1 0 1 0 0 2h2a1 1 0 1 0 0-2zM5 9a2 2 0 0 0-2 2v2.27A2 2 0 0 1 4 13h2c.365 0 .706.1 1 .27V11a2 2 0 0 0-2-2m5 0a2 2 0 0 0-2 2v2.27A2 2 0 0 1 9 13h2c.365 0 .706.1 1 .27V11a2 2 0 0 0-2-2m5 0a2 2 0 0 0-2 2v2.27a2 2 0 0 1 1-.27h2c.365 0 .706.1 1 .27V11a2 2 0 0 0-2-2M7.75 4A1.75 1.75 0 0 0 6 5.75v2.422a3 3 0 0 1 1.5 1.17a3 3 0 0 1 2-1.299V5.75A1.75 1.75 0 0 0 7.75 4m4.5 0a1.75 1.75 0 0 0-1.75 1.75v2.293a3 3 0 0 1 2 1.3A3 3 0 0 1 14 8.172V5.75A1.75 1.75 0 0 0 12.25 4");
}

</style>
