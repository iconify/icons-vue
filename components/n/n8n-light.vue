<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxeetebtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":96};
const content = `<path class="gxeetebtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:n8n-light" /></template>
