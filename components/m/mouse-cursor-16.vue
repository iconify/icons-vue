<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy4eacc9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cy4eacc9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mouse-cursor-16" /></template>
