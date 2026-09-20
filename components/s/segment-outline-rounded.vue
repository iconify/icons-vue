<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr00cokcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:segment-outline-rounded" /></template>
<style>
.vr00cokcm {
  fill: currentColor;
  d: path("M10.5 17.27q-.213 0-.356-.145T10 16.768t.144-.356t.356-.143h9q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm0-4.77q-.213 0-.356-.144T10 11.999t.144-.356t.356-.143h9q.213 0 .356.144t.144.357t-.144.356t-.356.143zm-6-4.77q-.213 0-.356-.143Q4 7.443 4 7.23t.144-.356t.356-.143h15q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
