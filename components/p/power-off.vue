<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwo9h3eho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwo9h3eho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-off" /></template>
