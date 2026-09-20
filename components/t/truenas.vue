<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy402objk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy402objk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:truenas" /></template>
