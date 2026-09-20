<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnf9gebbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnf9gebbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:siyuan" /></template>
