<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdh0-b5ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zdh0-b5ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:slidersmiddle" /></template>
