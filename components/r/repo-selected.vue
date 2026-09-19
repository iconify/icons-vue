<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_9ls9hrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_9ls9hrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-selected" /></template>
