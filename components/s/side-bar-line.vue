<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftgrlccva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftgrlccva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:side-bar-line" /></template>
