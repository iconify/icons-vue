<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv2fqxnsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-disabled-sharp" /></template>
<style>
.lv2fqxnsv {
  fill: currentColor;
  d: path("m17.1 14.35l-1.45-1.45q.225-.275.738-1t.637-1l-2.85-2.875L15.1 3H21v1.05q0 2.725-.975 5.3t-2.925 5M4.05 21H3v-5.875L8 14.1l2.9 2.9q.725-.45 1.138-.737t.762-.563L1.4 4.3l1.4-1.4l18.4 18.4l-1.4 1.4l-5.55-5.55q-2.3 1.875-4.925 2.863T4.05 21");
}

</style>
