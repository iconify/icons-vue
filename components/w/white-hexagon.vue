<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0nrgzb4b.css';
import '../../css/j/j4wwoicdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b0nrgzb4b"/><path class="j4wwoicdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-hexagon" /></template>
