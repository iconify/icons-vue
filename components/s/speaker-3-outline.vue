<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4uv6bcyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-3-outline" /></template>
<style>
.f4uv6bcyu {
  fill: currentColor;
  d: path("M7.346 19h9.289q.56 0 .962-.403q.403-.403.403-.982V5.386q0-.58-.403-.982Q17.194 4 16.634 4H7.346q-.56 0-.962.403q-.403.403-.403.982v12.23q0 .58.403.982q.402.403.962.403m1.346 2v-1H7.346q-.98 0-1.673-.702q-.692-.702-.692-1.682V5.385q0-.981.692-1.683Q6.366 3 7.346 3h9.289q.98 0 1.673.702q.692.702.692 1.683v12.23q0 .981-.692 1.683T16.634 20H15.27v1zM12 11.5");
}

</style>
