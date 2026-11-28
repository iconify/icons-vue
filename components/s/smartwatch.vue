<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzo26gbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzo26gbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartwatch" /></template>
