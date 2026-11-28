<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gplu-xtlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gplu-xtlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-star" /></template>
