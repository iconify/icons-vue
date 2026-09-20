<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx03psb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx03psb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mihoyo" /></template>
