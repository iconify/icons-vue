<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aghjl2bmp.css';
import '../../css/i/ic8mjabnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aghjl2bmp"/><path class="ic8mjabnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-snow-20-bold" /></template>
