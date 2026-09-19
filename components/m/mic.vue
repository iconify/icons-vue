<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c96awj_av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c96awj_av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mic" /></template>
