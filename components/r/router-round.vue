<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orig1-xyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orig1-xyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-round" /></template>
