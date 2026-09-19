<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba7791_9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ba7791_9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:subtract" /></template>
