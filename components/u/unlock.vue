<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd4l6dbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd4l6dbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:unlock" /></template>
