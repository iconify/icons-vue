<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqadkkxff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oqadkkxff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:react-wheel-picker-dark" /></template>
