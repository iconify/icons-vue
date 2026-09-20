<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0a0lpu5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0a0lpu5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:verse-light" /></template>
