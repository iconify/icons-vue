<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7t_cxwna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d7t_cxwna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vim" /></template>
