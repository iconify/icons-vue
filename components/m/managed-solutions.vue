<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzwywtzpa.css';
import '../../css/x/xvq7pg0gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dzwywtzpa"/><path class="xvq7pg0gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:managed-solutions" /></template>
