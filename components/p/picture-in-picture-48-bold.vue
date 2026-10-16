<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaet4wb5s.css';
import '../../css/z/z43empbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iaet4wb5s"/><path class="z43empbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picture-in-picture-48-bold" /></template>
