<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nis8n537v.css';
import '../../css/g/gz8l-pnrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nis8n537v"/><path class="gz8l-pnrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tobimake" /></template>
