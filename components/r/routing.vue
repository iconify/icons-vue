<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4eyxbbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s4eyxbbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:routing" /></template>
