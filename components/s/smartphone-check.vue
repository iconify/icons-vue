<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs6me8b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs6me8b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone-check" /></template>
