<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thwt89bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="thwt89bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tv-1-fill" /></template>
