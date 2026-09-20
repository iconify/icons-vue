<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mpc25-b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-32-filled" /></template>
<style>
.mpc25-b0n {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14l-.002.013c-.005 4.223-2.29 7.007-5.249 7.007c-1.74 0-3.248-.965-4.195-2.619C19.379 21.971 17.58 23 15.5 23C11.806 23 9 19.756 9 16c0-3.757 2.806-7 6.5-7a6.15 6.15 0 0 1 4 1.48v-.23a1.25 1.25 0 1 1 2.5 0V16c0 3.464 1.711 4.52 2.749 4.52s2.75-1.056 2.75-4.52v-.013C27.492 9.642 22.347 4.5 16 4.5C9.649 4.5 4.5 9.649 4.5 16S9.649 27.5 16 27.5c1.039 0 2.045-.14 3.002-.4c.485-.13 1.01-.017 1.366.338c.65.65.443 1.745-.438 2.002c-1.247.364-2.566.56-3.93.56c-7.732 0-14-6.268-14-14S8.268 2 16 2m-.5 9.5c-2.104 0-4 1.905-4 4.5s1.896 4.5 4 4.5s4-1.905 4-4.5s-1.895-4.5-4-4.5");
}

</style>
