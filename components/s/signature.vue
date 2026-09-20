<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn5gx4_1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yn5gx4_1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:signature" /></template>
