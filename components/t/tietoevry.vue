<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9a06w5xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9a06w5xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tietoevry" /></template>
