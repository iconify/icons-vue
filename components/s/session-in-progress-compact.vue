<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaaayhocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zaaayhocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:session-in-progress-compact" /></template>
