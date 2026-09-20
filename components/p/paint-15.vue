<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1rz5ob3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y1rz5ob3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:paint-15" /></template>
