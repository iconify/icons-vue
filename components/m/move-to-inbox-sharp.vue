<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbcxfuz1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-to-inbox-sharp" /></template>
<style>
.nbcxfuz1v {
  fill: currentColor;
  d: path("M12 13.308L8.692 10l.708-.72l2.1 2.1V6.693h1v4.689l2.1-2.1l.708.719zM4 20V4h16v16zm9.725-3.934q.775-.55 1.075-1.45H19V5H5v9.616h4.2q.3.9 1.075 1.45t1.725.55t1.725-.55");
}

</style>
