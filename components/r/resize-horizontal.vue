<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c34mxabax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="c34mxabax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:resize-horizontal" /></template>
