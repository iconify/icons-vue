<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuu31hbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuu31hbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:torch" /></template>
