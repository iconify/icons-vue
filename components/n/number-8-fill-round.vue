<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7573mrea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7573mrea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-8-fill-round" /></template>
