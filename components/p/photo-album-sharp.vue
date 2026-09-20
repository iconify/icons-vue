<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utpm5bcmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-album-sharp" /></template>
<style>
.utpm5bcmk {
  fill: currentColor;
  d: path("M5 21V3h14v18zm2.73-3.5h8.693l-2.74-3.654l-2.53 3.192l-1.605-1.925zM12 10.116l2-1.193l2 1.193V4h-4z");
}

</style>
