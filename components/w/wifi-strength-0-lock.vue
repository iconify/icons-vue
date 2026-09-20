<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_3q33btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_3q33btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-0-lock" /></template>
