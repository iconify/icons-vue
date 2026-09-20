<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuos9wz9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuos9wz9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seal-fill" /></template>
