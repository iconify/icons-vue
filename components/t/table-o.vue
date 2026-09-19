<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi682gbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1472};
const content = `<path class="fi682gbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:table-o" /></template>
