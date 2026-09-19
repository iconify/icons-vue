<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7612qess.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="w7612qess"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:paper-clip" /></template>
