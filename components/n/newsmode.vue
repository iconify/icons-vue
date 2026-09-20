<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep9yhub3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:newsmode" /></template>
<style>
.ep9yhub3c {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zm2.153-3.77h10.462v-1H6.769zm0-3.73h3.385V7.77H6.769zm5.77 0h4.692v-1h-4.693zm0-3.73h4.692v-1h-4.693z");
}

</style>
