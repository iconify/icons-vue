<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jua1gqqhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jua1gqqhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:multi-select-mirrored" /></template>
