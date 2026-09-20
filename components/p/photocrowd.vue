<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9753rbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9753rbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:photocrowd" /></template>
