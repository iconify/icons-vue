<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrgqosbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:message-bubble-pair" /></template>
<style>
.vrgqosbmi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 2.25h-7q-1.346 0-2.298.952T2.25 5.5V13q0 .227.126.416q.041.061.093.114q.052.052.114.093q.061.041.129.07q.068.028.141.042t.146.015q.074 0 .147-.014q.072-.015.14-.043t.13-.069l2.811-1.874H12.5q3.25 0 3.25-3.25v-3q0-3.25-3.25-3.25M11.5 13h7q1.346 0 2.298.952t.952 2.298V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.227 0-.416-.126l-2.811-1.874H11.5q-3.25 0-3.25-3.25v-.25Q8.25 13 11.5 13");
}

</style>
