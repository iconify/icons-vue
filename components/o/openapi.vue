<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjnly3blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xjnly3blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openapi" /></template>
