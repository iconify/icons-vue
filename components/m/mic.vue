<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_5cui5dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_5cui5dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mic" /></template>
