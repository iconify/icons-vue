<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_f48ibsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_f48ibsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-circle-fill-16" /></template>
