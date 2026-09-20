<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsacoyt2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jsacoyt2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:sign" /></template>
