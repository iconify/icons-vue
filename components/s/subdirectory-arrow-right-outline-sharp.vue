<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9rf4pbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subdirectory-arrow-right-outline-sharp" /></template>
<style>
.b9rf4pbkn {
  fill: currentColor;
  d: path("m14 20l-.713-.713l3.792-3.787H6V5h1v9.5h10.079l-3.792-3.792l.707-.714L19 15z");
}

</style>
