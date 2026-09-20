<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p41-95gdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p41-95gdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xml" /></template>
