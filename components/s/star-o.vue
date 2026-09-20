<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf-r26bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="zf-r26bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:star-o" /></template>
