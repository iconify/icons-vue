<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_v2zbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_v2zbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:snowflake" /></template>
