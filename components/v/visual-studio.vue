<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg2rnuewc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg2rnuewc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:visual-studio" /></template>
