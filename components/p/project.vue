<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz3ebhbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lz3ebhbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:project" /></template>
