<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3lugnbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j3lugnbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:triangle-16-solid" /></template>
