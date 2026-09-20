<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk1ibeynv.css';
import '../../css/y/yettion4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nk1ibeynv"/><path class="yettion4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-wi-fi" /></template>
