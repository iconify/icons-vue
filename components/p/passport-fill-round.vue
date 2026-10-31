<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hks2i43dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hks2i43dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-fill-round" /></template>
