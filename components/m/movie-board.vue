<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4sbyjb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l4sbyjb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:movie-board" /></template>
