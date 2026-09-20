<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dix984blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pill-28-filled" /></template>
<style>
.dix984blz {
  fill: currentColor;
  d: path("M15.78 3.744c2.34-2.337 6.137-2.328 8.475.01c2.34 2.34 2.346 6.142.004 8.481l-12.038 12.02c-2.34 2.337-6.137 2.328-8.475-.01c-2.34-2.34-2.346-6.142-.004-8.48zm1.933 12.908l5.486-5.478a4.5 4.5 0 0 0-.005-6.36a4.5 4.5 0 0 0-6.354-.009l-5.49 5.483zm-5.932 4.628a.75.75 0 0 0-1.06-1.06l-1.978 1.977a1.05 1.05 0 0 1-1.484 0l-.478-.477a.75.75 0 0 0-1.06 1.06l.477.477a2.55 2.55 0 0 0 3.606 0z");
}

</style>
