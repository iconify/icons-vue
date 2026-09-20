<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j68hkvbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j68hkvbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:thumbs-down" /></template>
