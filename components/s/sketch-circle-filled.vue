<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axj77dh9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="axj77dh9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sketch-circle-filled" /></template>
