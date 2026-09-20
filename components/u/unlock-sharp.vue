<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f42v76bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f42v76bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:unlock-sharp" /></template>
