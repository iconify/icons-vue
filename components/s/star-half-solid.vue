<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrohoebxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrohoebxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:star-half-solid" /></template>
