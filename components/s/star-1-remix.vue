<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8nzyib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b8nzyib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-1-remix" /></template>
