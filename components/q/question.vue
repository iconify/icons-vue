<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm0ouabjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fm0ouabjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:question" /></template>
