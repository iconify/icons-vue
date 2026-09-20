<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p07u0ub0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-decrease-sharp" /></template>
<style>
.p07u0ub0o {
  fill: currentColor;
  d: path("m1.616 18.5l5.288-13h.962l5.288 13h-1.208l-1.448-3.633H4.194L2.746 18.5zm2.938-4.6h5.584L7.436 7.1h-.139zm10.83-1.4v-1h7v1z");
}

</style>
