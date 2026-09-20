<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3k2rk00f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3k2rk00f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nokia" /></template>
