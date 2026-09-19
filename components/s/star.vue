<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjb74fbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjb74fbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:star" /></template>
