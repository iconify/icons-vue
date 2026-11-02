<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iks4w9psj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iks4w9psj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:middle-finger-fill" /></template>
