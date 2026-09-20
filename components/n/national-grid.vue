<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c84_js1xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c84_js1xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:national-grid" /></template>
