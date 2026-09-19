<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhmtbxdza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fhmtbxdza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sketch-square-fill" /></template>
