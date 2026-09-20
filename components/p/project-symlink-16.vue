<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpnn3uu-g.css';
import '../../css/j/jletztwxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tpnn3uu-g"/><path class="jletztwxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-symlink-16" /></template>
