<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdm-cibjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdm-cibjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:paper-plane" /></template>
