<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwdo78b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwdo78b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:slides" /></template>
