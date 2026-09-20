<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihkyc8rwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:money-off-outline" /></template>
<style>
.ihkyc8rwj {
  fill: currentColor;
  d: path("M14.35 8.53q-.3-.75-.887-1.174T12.05 6.93q-.45 0-.952.163q-.502.164-.852.572l-.719-.72q.37-.407.921-.656q.552-.25 1.052-.305V4.346h1v1.627q.817.09 1.59.605q.774.514 1.199 1.557zm4.989 12.224l-4.177-4.177q-.414.587-1.16.988q-.746.4-1.502.412v1.639h-1v-1.689q-1.246-.235-1.991-1.025t-1.17-2.075l.961-.377q.32 1.05 1.022 1.8q.703.75 1.878.75q.72 0 1.296-.314q.577-.315.946-.828L3.246 4.662l.708-.708l16.092 16.092z");
}

</style>
