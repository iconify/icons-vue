<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiuto9r3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiuto9r3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-forward-box-fill" /></template>
