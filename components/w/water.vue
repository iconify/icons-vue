<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0kt2-bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0kt2-bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:water" /></template>
