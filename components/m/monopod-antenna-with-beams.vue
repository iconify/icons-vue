<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-v94cnaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j-v94cnaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:monopod-antenna-with-beams" /></template>
