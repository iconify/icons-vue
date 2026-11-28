<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adcbp-yaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adcbp-yaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:traffic-light-alert" /></template>
