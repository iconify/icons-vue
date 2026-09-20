<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3vjjyk8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j3vjjyk8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:martini-glass-and-wine-bottle" /></template>
