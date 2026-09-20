<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulul0ib1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulul0ib1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uipath" /></template>
