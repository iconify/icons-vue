<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2hq86blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="r2hq86blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:play-square" /></template>
