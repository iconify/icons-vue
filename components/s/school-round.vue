<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jacd5s40q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jacd5s40q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-round" /></template>
