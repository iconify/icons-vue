<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8uaq-bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8uaq-bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sd-card" /></template>
