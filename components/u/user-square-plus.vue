<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkt3i8kst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkt3i8kst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-square-plus" /></template>
