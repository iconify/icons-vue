<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcgh90ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcgh90ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wardrobe-solid" /></template>
