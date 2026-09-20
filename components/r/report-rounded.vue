<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdmexccmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:report-rounded" /></template>
<style>
.kdmexccmx {
  fill: currentColor;
  d: path("M12 16.423q.262 0 .439-.182t.176-.433t-.177-.434t-.438-.182t-.438.182t-.177.434t.177.433t.438.182m.357-3.105q.143-.144.143-.356V7.885q0-.213-.144-.357t-.357-.143t-.356.143t-.143.357v5.077q0 .212.144.356t.357.144t.356-.144M9.344 20q-.331 0-.632-.13t-.518-.349L4.48 15.806q-.217-.217-.348-.518T4 14.656V9.344q0-.331.13-.632t.349-.518L8.194 4.48q.217-.218.518-.348T9.344 4h5.312q.331 0 .632.13t.518.349l3.715 3.715q.218.217.348.518t.131.632v5.312q0 .331-.13.632t-.349.518l-3.715 3.715q-.217.218-.518.348t-.632.131z");
}

</style>
