<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0el-pkyw.css';
import '../../css/j/j8yh1x58g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v0el-pkyw"/><path class="j8yh1x58g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pcn-p-node" /></template>
