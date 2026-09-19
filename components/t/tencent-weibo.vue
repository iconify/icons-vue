<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy2-pue0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fy2-pue0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tencent-weibo" /></template>
