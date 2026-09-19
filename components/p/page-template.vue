<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl-k7xb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hl-k7xb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:page-template" /></template>
