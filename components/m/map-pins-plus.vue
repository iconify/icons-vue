<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4i5kyb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i5kyb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pins-plus" /></template>
