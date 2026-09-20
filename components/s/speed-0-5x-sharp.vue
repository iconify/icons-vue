<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9h3gacma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-5x-sharp" /></template>
<style>
.o9h3gacma {
  fill: currentColor;
  d: path("M4 16.5v-1h1v1zm9.27 0l2.807-4.692L13.5 7.5h1.116l2.019 3.383L18.654 7.5h1.077l-2.558 4.27L20 16.5h-1.115l-2.27-3.786l-2.269 3.786zm-6.77 0v-1h4v-3h-4v-5h5v1h-4v3h4v5z");
}

</style>
