<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhflvyeci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhflvyeci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:note-text-line" /></template>
