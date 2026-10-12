<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2hel0pen.css';
import '../../css/b/b5hazkbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2hel0pen"/><path class="b5hazkbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-chip-20-bold" /></template>
