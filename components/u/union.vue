<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kod4j6bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kod4j6bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:union" /></template>
