<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikm53ybyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikm53ybyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:moscow-metro" /></template>
