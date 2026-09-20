<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4apqiecb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4apqiecb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sublime" /></template>
