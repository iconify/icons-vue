<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v24ulvjer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":260,"height":260};
const content = `<path class="v24ulvjer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:odin" /></template>
