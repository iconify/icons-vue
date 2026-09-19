<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f64a5abnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f64a5abnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:truck-field" /></template>
