<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sabln9pcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sabln9pcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:testin" /></template>
