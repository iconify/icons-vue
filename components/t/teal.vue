<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5_mjzf7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5_mjzf7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:teal" /></template>
