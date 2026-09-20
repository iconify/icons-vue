<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzj1nzb2x.css';
import '../../css/v/vwu041i_f.css';
import '../../css/h/h0cxnwb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qzj1nzb2x"/><path class="vwu041i_f"/><path class="h0cxnwb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-file-picture" /></template>
