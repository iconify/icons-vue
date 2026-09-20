<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hboc7ybci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hboc7ybci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:proteus" /></template>
