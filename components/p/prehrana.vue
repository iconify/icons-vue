<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pkopikb2q"/><path class="jllinyxoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prehrana" /></template>
<style>
.jllinyxoe {
  d: path("M24.274 14.385c-1.012-3.628.791-6.554 2.142-7.628c1.308-1.04 3.105-2.488 7.054-2.226c.065 2.358-.859 4.643-2.081 5.666c-1.223 1.023-3.542 1.442-4.825 2.288s-2.29 1.9-2.29 1.9");
}

.pkopikb2q {
  d: path("M24.133 43.5C35.303 35.884 39.79 30.554 39.9 23.678c.11-6.878-4.476-10.721-7.896-10.704c-5.728.03-7.788 4.038-7.788 4.038s-2.633-4.063-8.507-3.54c-5.006.447-7.69 5.662-7.609 9.414s.928 7.028 7.387 10.674c3.556 2.008 8.538 6.468 8.646 9.94");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
