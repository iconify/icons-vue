<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7gnsebfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j7gnsebfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:microscope-observation-sciene" /></template>
