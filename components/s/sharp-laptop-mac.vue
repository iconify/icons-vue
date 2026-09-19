<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjs8bz9ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-laptop-mac" /></template>
<style>
.gjs8bz9ek {
  fill: currentColor;
  d: path("m20 18l1.99-2L22 3H2v13l2 2H0v2h24v-2zM4 5h16v11H4zm8 14c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
