<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvqgxcehq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pediatrics-outline-sharp" /></template>
<style>
.nvqgxcehq {
  fill: currentColor;
  d: path("M7 7V5h4V2h2v3h4v2zm0 15V11q0-1.25.875-2.125T10 8h4q1.25 0 2.125.875T17 11v11zm2-2h6v-9q0-.425-.288-.712T14 10h-4q-.425 0-.712.288T9 11v1h3v2H9v2h3v2H9zm0 0V10z");
}

</style>
