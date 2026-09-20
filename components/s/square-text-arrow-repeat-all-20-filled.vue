<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vw6v8vb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-text-arrow-repeat-all-20-filled" /></template>
<style>
.vw6v8vb7e {
  fill: currentColor;
  d: path("m16.06 8.94l.94.939V5.5A2.5 2.5 0 0 0 14.5 3h-9A2.5 2.5 0 0 0 3 5.5v9A2.5 2.5 0 0 0 5.5 17h5.47a1.5 1.5 0 0 1-1.17-.599A4 4 0 0 1 9 14H6.5l-.09-.008a.5.5 0 0 1 0-.984L6.5 13h2.626a4 4 0 0 1 1.936-2.5H6.5l-.09-.008a.5.5 0 0 1 0-.984L6.5 9.5h7l.083.007a1.5 1.5 0 0 1 2.478-.568M14 6.5a.5.5 0 0 1-.41.492L13.5 7h-7l-.09-.008a.5.5 0 0 1 0-.984L6.5 6h7l.09.008A.5.5 0 0 1 14 6.5m1.354 3.146a.5.5 0 0 0-.708.708l.647.646H13a3 3 0 0 0-2.4 4.8a.5.5 0 1 0 .8-.6A2 2 0 0 1 13 12h2.293l-.647.646a.5.5 0 0 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708zM18.4 12.2a.5.5 0 0 0-.8.6A2 2 0 0 1 16 16h-2.293l.647-.646a.5.5 0 0 0-.708-.708l-1.5 1.5a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708L13.707 17H16a3 3 0 0 0 2.4-4.8");
}

</style>
