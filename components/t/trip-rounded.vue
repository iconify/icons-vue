<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u764nldtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trip-rounded" /></template>
<style>
.u764nldtz {
  fill: currentColor;
  d: path("M17 20V7h2.385q.69 0 1.152.463T21 8.616v9.769q0 .69-.463 1.153T19.385 20zM10 7h4V5.615q0-.23-.192-.423T13.385 5h-2.77q-.23 0-.423.192T10 5.615zM8 20V7h1V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h1v13zm-3.384 0q-.691 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H7v13z");
}

</style>
