<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0778l-1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0778l-1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stamp-filled" /></template>
