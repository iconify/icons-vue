<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o971i99qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o971i99qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:subway-line-filled" /></template>
