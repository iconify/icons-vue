<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc57nxbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc57nxbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tool-box" /></template>
