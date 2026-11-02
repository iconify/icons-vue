<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5_utsc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5_utsc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitter-line" /></template>
