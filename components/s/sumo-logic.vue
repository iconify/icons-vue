<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esij82b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esij82b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sumo-logic" /></template>
