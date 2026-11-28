<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssfjm-b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssfjm-b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pin-info" /></template>
