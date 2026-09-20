<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyiq1bcaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyiq1bcaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil" /></template>
