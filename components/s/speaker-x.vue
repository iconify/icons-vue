<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhx7cdbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhx7cdbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:speaker-x" /></template>
