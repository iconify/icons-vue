<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk17zl5nv.css';
import '../../css/q/qjhu6dbua.css';
import '../../css/t/tz_5mvbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bk17zl5nv"/><path class="qjhu6dbua"/><path class="tz_5mvbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:web-services-task-definition-version" /></template>
