<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwi-3lbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwi-3lbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:postman" /></template>
