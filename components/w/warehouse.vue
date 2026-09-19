<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj53t6bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zj53t6bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:warehouse" /></template>
