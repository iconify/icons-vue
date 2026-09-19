<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh7bkobdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="yh7bkobdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:picture" /></template>
