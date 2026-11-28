<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-q0c7bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-q0c7bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-lock" /></template>
