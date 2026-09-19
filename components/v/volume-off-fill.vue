<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdkq4lblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fdkq4lblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-off-fill" /></template>
