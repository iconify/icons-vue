<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhm3v8bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhm3v8bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-off" /></template>
