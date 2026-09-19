<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt3uovblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lt3uovblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:obsidian" /></template>
