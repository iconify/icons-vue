<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oq6vzj3wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-32-light" /></template>
<style>
.oq6vzj3wn {
  fill: currentColor;
  d: path("M12 12.001V20a1 1 0 0 0 1.47.882l7.498-3.999a1 1 0 0 0 0-1.764l-7.497-3.999a1 1 0 0 0-1.471.882M6.5 28h19a4.5 4.5 0 0 0 4.5-4.5v-15A4.5 4.5 0 0 0 25.5 4h-19A4.5 4.5 0 0 0 2 8.5v15A4.5 4.5 0 0 0 6.5 28m19-1h-19A3.5 3.5 0 0 1 3 23.5v-15A3.5 3.5 0 0 1 6.5 5h19A3.5 3.5 0 0 1 29 8.5v15a3.5 3.5 0 0 1-3.5 3.5");
}

</style>
