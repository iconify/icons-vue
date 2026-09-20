<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpirlyb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gpirlyb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:search-16" /></template>
