<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-dnxbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-dnxbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-align-center-box-sharp" /></template>
