<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd5n43due.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yd5n43due"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stopwatch-16" /></template>
