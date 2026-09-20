<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxk9vrbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:share-windows-sharp" /></template>
<style>
.zxk9vrbqg {
  fill: currentColor;
  d: path("M7.5 14.5v-7h10.573l-3.075-3.075l.714-.713L20 8l-4.288 4.308l-.714-.708l3.075-3.1H8.5v6zM4 20V4.616h1V19h12v-4.5h1V20z");
}

</style>
