<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__5tx9hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i__5tx9hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stepzen-graph-server" /></template>
