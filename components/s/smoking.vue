<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zixferb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="zixferb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:smoking" /></template>
