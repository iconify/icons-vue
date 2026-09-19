<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxmoz7bla.css';
import '../../css/y/y4npxtoda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxmoz7bla"/><path class="y4npxtoda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tree" /></template>
