<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi4rw9ffy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pi4rw9ffy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sliders-fill" /></template>
