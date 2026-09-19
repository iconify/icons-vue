<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiix5obts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hiix5obts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tablet-screen-button" /></template>
