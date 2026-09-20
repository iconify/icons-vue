<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqhu_g8oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zqhu_g8oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:triangle-left" /></template>
