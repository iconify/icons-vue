<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smepu6bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smepu6bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:thunderstorm" /></template>
