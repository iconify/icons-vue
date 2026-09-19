<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw9l9zbzr.css';
import '../../css/g/gjykr6brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aw9l9zbzr"/><path class="gjykr6brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:result-draft" /></template>
