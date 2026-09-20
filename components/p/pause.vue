<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv0s08bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zv0s08bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:pause" /></template>
