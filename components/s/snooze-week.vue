<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx3t7-i1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nx3t7-i1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:snooze-week" /></template>
