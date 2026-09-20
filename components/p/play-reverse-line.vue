<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj9kt2-kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj9kt2-kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-reverse-line" /></template>
