<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdm7rhbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdm7rhbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-365-dark" /></template>
