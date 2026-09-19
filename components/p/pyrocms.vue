<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j01bfxbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":642,"height":1025};
const content = `<path class="j01bfxbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pyrocms" /></template>
