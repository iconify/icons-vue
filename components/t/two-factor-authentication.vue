<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drvhp1nhb.css';
import '../../css/e/ew-j63_wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drvhp1nhb"/><path class="ew-j63_wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:two-factor-authentication" /></template>
