<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y54jv0b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trending-flat-outline-sharp" /></template>
<style>
.y54jv0b_u {
  fill: currentColor;
  d: path("m17.192 15.808l-.713-.708l2.6-2.6H4v-1h15.079l-2.594-2.6l.713-.708L21 12z");
}

</style>
