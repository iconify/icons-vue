<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3wopibcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v3wopibcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:scroll-unlock-16" /></template>
