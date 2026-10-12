<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtq1wfort.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtq1wfort"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:music-2-filled" /></template>
