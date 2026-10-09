<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fulicxqoo.css';
import '../../css/e/e8evysbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fulicxqoo"/><path class="e8evysbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunset-20-bold" /></template>
