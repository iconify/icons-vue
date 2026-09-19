<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo0nwpb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qo0nwpb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:thinking" /></template>
