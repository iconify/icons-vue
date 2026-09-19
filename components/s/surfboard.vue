<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3hlxjb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3hlxjb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:surfboard" /></template>
