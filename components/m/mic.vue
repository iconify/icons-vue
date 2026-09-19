<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnqn87_3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="xnqn87_3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:mic" /></template>
