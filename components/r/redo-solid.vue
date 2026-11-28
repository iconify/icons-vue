<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbb5ozubs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbb5ozubs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:redo-solid" /></template>
