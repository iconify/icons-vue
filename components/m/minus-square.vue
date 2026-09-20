<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gewabquhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gewabquhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:minus-square" /></template>
