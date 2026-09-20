<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-b4btjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gh-b4btjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:microphone-outline" /></template>
