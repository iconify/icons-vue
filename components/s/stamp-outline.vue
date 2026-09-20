<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9jl1r7rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j9jl1r7rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:stamp-outline" /></template>
