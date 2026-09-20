<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npblpyoji.css';
import '../../css/j/jm3xaac9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="npblpyoji"/><path class="jm3xaac9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:whatsapp" /></template>
