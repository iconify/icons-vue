<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6wxn2day.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6wxn2day"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pentagon-dashed-solid" /></template>
