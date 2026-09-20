<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9jmp33sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9jmp33sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-3-1" /></template>
