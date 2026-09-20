<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0f3jeb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0f3jeb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rake-fill" /></template>
