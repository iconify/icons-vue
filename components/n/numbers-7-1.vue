<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb2tv0bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb2tv0bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-7-1" /></template>
