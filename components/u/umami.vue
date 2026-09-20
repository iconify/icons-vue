<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skbd124kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skbd124kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:umami" /></template>
