<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i13n2kjog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i13n2kjog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mixcloud" /></template>
