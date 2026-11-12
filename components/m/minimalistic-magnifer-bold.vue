<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csocnccks"/><path clip-rule="evenodd" class="llqf1f1jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bold" /></template>
<style>
.csocnccks {
  fill: currentColor;
  d: path("M20.313 11.157a9.157 9.157 0 1 1-18.313 0a9.157 9.157 0 0 1 18.313 0");
}

.llqf1f1jk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.838 18.838a.723.723 0 0 1 1.023 0l1.927 1.928a.723.723 0 0 1-1.022 1.022l-1.928-1.927a.723.723 0 0 1 0-1.023");
}

</style>
