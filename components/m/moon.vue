<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk3a44bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jk3a44bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:moon" /></template>
