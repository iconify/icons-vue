<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hap7ambrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hap7ambrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:whatsapp-square" /></template>
