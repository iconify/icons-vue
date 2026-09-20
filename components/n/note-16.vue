<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2d7aoyzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2d7aoyzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:note-16" /></template>
