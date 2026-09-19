<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9spjjbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="j9spjjbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:resistance" /></template>
