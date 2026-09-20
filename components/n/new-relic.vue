<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfz2y4bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfz2y4bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:new-relic" /></template>
