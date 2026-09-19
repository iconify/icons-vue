<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0c1-ogyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y0c1-ogyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:snowman" /></template>
