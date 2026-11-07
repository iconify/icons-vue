<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxpc884id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pull-request-rounded" /></template>
<style>
.gxpc884id {
  fill: currentColor;
  d: path("M16.914 20.27q-.703-.693-.703-1.674q0-.835.541-1.497q.54-.663 1.364-.828v-8.58q-.708-.149-1.203-.633q-.494-.485-.642-1.192h-4.923l1.948 1.992q.14.16.15.354t-.15.334t-.363.15t-.344-.15L9.78 5.7q-.14-.14-.14-.344t.14-.344l2.808-2.827q.159-.16.353-.16t.354.16q.14.14.14.344t-.14.344l-1.948 1.993h4.923q.166-.824.828-1.354t1.517-.531q1 0 1.692.692q.692.693.692 1.693q0 .834-.53 1.497t-1.354.828v8.58q.823.166 1.353.819q.531.652.531 1.487q0 1-.692 1.692t-1.693.693t-1.702-.693m-11.529.693q-.98 0-1.682-.693Q3 19.577 3 18.596q0-.834.53-1.497t1.355-.828v-8.58q-.823-.166-1.354-.828T3 5.366q0-1 .692-1.693q.692-.692 1.693-.692t1.702.692t.702 1.693q0 .834-.541 1.497q-.54.662-1.364.828v8.58q.824.166 1.364.819t.54 1.487q0 1-.702 1.692t-1.702.693");
}

</style>
