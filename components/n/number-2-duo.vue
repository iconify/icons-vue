<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0o8vnbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0o8vnbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-2-duo" /></template>
