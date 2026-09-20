<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l61x-mbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l61x-mbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sitecore" /></template>
