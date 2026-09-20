<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8y93jb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:present-to-all-outline-sharp" /></template>
<style>
.b8y93jb5i {
  fill: currentColor;
  d: path("M11.5 15.308h1v-4.689l2.1 2.095l.713-.714L12 8.692L8.692 12l.714.708l2.094-2.094zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
