<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5ux0lp4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5ux0lp4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:projector-x" /></template>
