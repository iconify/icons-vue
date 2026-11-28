<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx0811s7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0811s7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:radio-off" /></template>
