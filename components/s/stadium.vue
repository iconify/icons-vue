<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3nly0bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3nly0bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stadium" /></template>
