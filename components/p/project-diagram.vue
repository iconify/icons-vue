<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqqa0bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="shqqa0bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:project-diagram" /></template>
