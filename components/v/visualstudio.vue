<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3k5mabfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k3k5mabfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:visualstudio" /></template>
