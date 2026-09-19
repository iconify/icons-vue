<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jalxl4brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jalxl4brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:thunderstorm" /></template>
