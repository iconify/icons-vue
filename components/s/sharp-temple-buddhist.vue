<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7s2afb3b"/><path class="ogfespbiu"/><path class="cag40dbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-temple-buddhist" /></template>
<style>
.cag40dbha {
  fill: currentColor;
  d: path("M12 1L8.25 6h7.5z");
}

.ogfespbiu {
  fill: currentColor;
  d: path("M6 8.86V10h12V8.86c.55-.14 3-1.04 3-3.86l-2 .02C19 6.11 18.11 7 17.02 7H6.98C5.89 7 5 6.11 5 5.02H3c0 1.85 1.28 3.4 3 3.84");
}

.p7s2afb3b {
  fill: currentColor;
  d: path("M21 9.02c0 1.09-.89 1.98-1.98 1.98H4.98C3.89 11 3 10.11 3 9.02H1c0 1.86 1.28 3.4 3 3.84V22h6v-5h4v5h6v-9.14c.55-.14 3-1.04 3-3.86z");
}

</style>
