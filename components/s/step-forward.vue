<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88x78b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t88x78b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:step-forward" /></template>
