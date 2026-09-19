<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho_1kcwhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho_1kcwhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:recording" /></template>
