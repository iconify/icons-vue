<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhl70gudo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zhl70gudo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:modx" /></template>
