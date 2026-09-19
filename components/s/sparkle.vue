<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8gi1jgjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b8gi1jgjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sparkle" /></template>
