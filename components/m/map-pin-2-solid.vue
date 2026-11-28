<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5r3cacbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5r3cacbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-2-solid" /></template>
