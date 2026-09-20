<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu97qhbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more-up-outline-sharp" /></template>
<style>
.vu97qhbcd {
  fill: currentColor;
  d: path("M17.5 15.539V6.5H9v-1h9.5v10.039zm-5 5V11.5H4v-1h9.5v10.039z");
}

</style>
