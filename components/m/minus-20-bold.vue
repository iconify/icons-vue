<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rldubof9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rldubof9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minus-20-bold" /></template>
