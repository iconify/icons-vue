<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snthn3bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snthn3bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical" /></template>
