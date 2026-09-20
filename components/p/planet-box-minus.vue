<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y59ojvwlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y59ojvwlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:planet-box-minus" /></template>
