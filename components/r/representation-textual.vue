<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zycd0oq2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zycd0oq2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:representation-textual" /></template>
