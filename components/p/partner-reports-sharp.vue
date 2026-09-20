<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzeld7bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:partner-reports-sharp" /></template>
<style>
.fzeld7bks {
  fill: currentColor;
  d: path("M11 13V3h2v10zm-8 8v-5h2v3h14v-3h2v5zm8-4v-2h2v2z");
}

</style>
