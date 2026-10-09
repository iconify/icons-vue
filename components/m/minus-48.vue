<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_knjioaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_knjioaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minus-48" /></template>
