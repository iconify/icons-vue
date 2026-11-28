<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj7wmugld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj7wmugld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mouse-x" /></template>
