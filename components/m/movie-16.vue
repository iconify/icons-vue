<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4r-65a1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g4r-65a1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:movie-16" /></template>
