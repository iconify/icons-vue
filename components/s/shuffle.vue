<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv6kmxbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zv6kmxbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shuffle" /></template>
