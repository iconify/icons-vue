<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r483jr0qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r483jr0qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-x-twitter" /></template>
