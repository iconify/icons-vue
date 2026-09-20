<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydl-c6bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydl-c6bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:uml" /></template>
