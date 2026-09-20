<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl_9klezh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-3-rounded" /></template>
<style>
.zl_9klezh {
  fill: currentColor;
  d: path("M7.346 20q-.98 0-1.673-.702q-.692-.702-.692-1.682V5.385q0-.981.692-1.683Q6.366 3 7.346 3h9.289q.98 0 1.673.702q.692.702.692 1.683v12.23q0 .981-.692 1.683T16.634 20H15.27v.192q0 .349-.24.578q-.238.23-.567.23H9.5q-.348 0-.578-.23t-.23-.578V20z");
}

</style>
