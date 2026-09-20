<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw2qxfbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vw2qxfbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mint" /></template>
