<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy0o8cbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jy0o8cbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:w" /></template>
