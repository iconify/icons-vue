<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg9q3cbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg9q3cbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-play-filled" /></template>
