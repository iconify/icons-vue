<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff2r-ybjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff2r-ybjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:telegraph" /></template>
