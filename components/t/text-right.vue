<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz0560box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xz0560box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:text-right" /></template>
