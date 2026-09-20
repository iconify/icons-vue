<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de-x6ubrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="de-x6ubrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:size-actual" /></template>
