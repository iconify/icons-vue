<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hym4oacfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-wake-on-press-sharp" /></template>
<style>
.hym4oacfh {
  fill: currentColor;
  d: path("M19.23 11.962V5H21v6.962zM7.217 20l-4.639-4.663l.835-.84l3.819.753V5.27q0-.53.37-.9T8.5 4t.899.37t.37.9v5.46h1.227l5.025 2.497L14.908 20z");
}

</style>
