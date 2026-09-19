<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1qzedbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-h-plus-mobiledata" /></template>
<style>
.f1qzedbqz {
  fill: currentColor;
  d: path("M12 11H6V7H4v10h2v-4h6v4h2V7h-2zm10 0h-2V9h-2v2h-2v2h2v2h2v-2h2z");
}

</style>
