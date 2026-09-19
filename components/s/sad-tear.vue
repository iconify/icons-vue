<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty2bzmojf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ty2bzmojf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sad-tear" /></template>
