<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgd7_gbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgd7_gbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-off" /></template>
