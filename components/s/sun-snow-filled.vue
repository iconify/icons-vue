<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4020bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4020bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-snow-filled" /></template>
