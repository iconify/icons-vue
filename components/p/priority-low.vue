<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1-w6z7eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1-w6z7eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:priority-low" /></template>
