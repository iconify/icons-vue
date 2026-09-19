<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk1ssk6fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk1ssk6fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:telegram" /></template>
