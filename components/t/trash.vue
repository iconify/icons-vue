<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-b55xleh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b55xleh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trash" /></template>
