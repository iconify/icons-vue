<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn8v5vbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bn8v5vbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paperclip-20-bold" /></template>
