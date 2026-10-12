<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5jbthbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5jbthbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-circle-stroke-20" /></template>
