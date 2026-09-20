<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzkp8bbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkp8bbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yamaha-motor-corporation" /></template>
