<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixyy18bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ixyy18bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tumblr-square" /></template>
