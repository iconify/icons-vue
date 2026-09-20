<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t7ktk9bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stove-16-filled" /></template>
<style>
.t7ktk9bay {
  fill: currentColor;
  d: path("M11 13a1 1 0 1 1 0 2H5a1 1 0 1 1 0-2zm3-7a1 1 0 1 1 0 2h-2v1.5A2.5 2.5 0 0 1 9.5 12h-3A2.5 2.5 0 0 1 4 9.5v-2A1.5 1.5 0 0 1 5.5 6zM2.5 1a.5.5 0 0 1 .5.5c0 .47.275.706.8 1.1l.04.03C4.314 2.985 5 3.498 5 4.5a.5.5 0 0 1-1 0c0-.47-.275-.706-.8-1.1l-.04-.03C2.686 3.015 2 2.502 2 1.5a.5.5 0 0 1 .5-.5m3 0a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03C7.314 2.985 8 3.498 8 4.5a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C5.686 3.015 5 2.502 5 1.5a.5.5 0 0 1 .5-.5m3 0a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03c.474.355 1.16.868 1.16 1.87a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C8.686 3.015 8 2.502 8 1.5a.5.5 0 0 1 .5-.5");
}

</style>
