<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7t8q-b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7t8q-b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:star" /></template>
