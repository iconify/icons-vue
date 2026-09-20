<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq3t__btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-overscan-outline-sharp" /></template>
<style>
.gq3t__btd {
  fill: currentColor;
  d: path("M6.846 13.616v-3.231L5.231 12zM12 16.769l1.616-1.615h-3.231zm-1.616-7.923h3.231L12 7.231zm6.77 4.77L18.769 12l-1.615-1.616zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
