<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhs768oih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sell-outline-sharp" /></template>
<style>
.yhs768oih {
  fill: currentColor;
  d: path("M12.825 22.825L2 12V2h10l10.8 10.85zm0-2.825l7.15-7.15L11.15 4H4v7.15zM6.5 8q.625 0 1.063-.437T8 6.5t-.437-1.062T6.5 5t-1.062.438T5 6.5t.438 1.063T6.5 8m5.5 4");
}

</style>
