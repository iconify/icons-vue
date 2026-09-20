<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwsgpxbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="dwsgpxbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:screen-f" /></template>
