<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjjbnrbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjjbnrbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-heart-solid" /></template>
