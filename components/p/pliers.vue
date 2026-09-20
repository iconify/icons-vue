<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usa70rbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usa70rbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pliers" /></template>
