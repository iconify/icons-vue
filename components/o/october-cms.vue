<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhfdrr6ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhfdrr6ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:october-cms" /></template>
