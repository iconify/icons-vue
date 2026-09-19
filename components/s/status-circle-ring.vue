<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq5_v9auw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xq5_v9auw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:status-circle-ring" /></template>
