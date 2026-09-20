<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5q0w7gwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5q0w7gwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:taxi" /></template>
