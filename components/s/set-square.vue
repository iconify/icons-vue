<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yci7k2x8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="yci7k2x8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:set-square" /></template>
