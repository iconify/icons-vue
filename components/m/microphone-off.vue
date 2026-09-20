<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff0bb0b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff0bb0b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:microphone-off" /></template>
