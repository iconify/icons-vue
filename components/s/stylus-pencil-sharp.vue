<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks3qzdbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pencil-sharp" /></template>
<style>
.ks3qzdbnx {
  fill: currentColor;
  d: path("m6 16l5-13h2l5 13zm-2 5l1-3h14l1 3z");
}

</style>
