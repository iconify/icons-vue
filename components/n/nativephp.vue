<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j47j3_blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j47j3_blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nativephp" /></template>
