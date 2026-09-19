<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fncz_m7by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="fncz_m7by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake" /></template>
