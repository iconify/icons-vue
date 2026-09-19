<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi2tssbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fi2tssbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:republican" /></template>
