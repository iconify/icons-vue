<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-uunxc6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-uunxc6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-roller-round" /></template>
