<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9qjnk78v.css';
import '../../css/j/jsw558btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9qjnk78v"/><path class="jsw558btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milestone-20-bold" /></template>
