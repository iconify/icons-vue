<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o03ka8bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unarchive-sharp" /></template>
<style>
.o03ka8bkh {
  fill: currentColor;
  d: path("m12 10.577l-3.308 3.308l.708.707l2.1-2.1v4.7h1v-4.7l2.1 2.1l.708-.707zM4 20V6.916L6.416 4h11.15L20 6.954V20zM5.38 6.808H18.6L17.096 5H6.885z");
}

</style>
