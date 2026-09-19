<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmr6bcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-bento" /></template>
<style>
.zcmr6bcrf {
  fill: currentColor;
  d: path("M16 11V5h4c1.1 0 2 .9 2 2v4zm4 8c1.1 0 2-.9 2-2v-4h-6v6zM14 5v14H4c-1.1 0-2-.9-2-2V7c0-1.1.9-2 2-2zm-4.5 7c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5s.67 1.5 1.5 1.5s1.5-.67 1.5-1.5");
}

</style>
