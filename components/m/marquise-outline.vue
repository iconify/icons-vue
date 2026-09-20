<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1em_sbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1em_sbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:marquise-outline" /></template>
