<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fulicxqoo.css';
import '../../css/s/syle989sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fulicxqoo"/><path class="syle989sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunrise-20-bold" /></template>
