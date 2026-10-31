<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z20hp9aer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z20hp9aer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:orbit-round" /></template>
