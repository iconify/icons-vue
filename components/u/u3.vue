<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a21g7ybtt.css';
import '../../css/o/ogc9qccuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a21g7ybtt"/><path class="ogc9qccuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:u3" /></template>
