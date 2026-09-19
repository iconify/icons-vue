<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1uqju2bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e1uqju2bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:split-discard" /></template>
