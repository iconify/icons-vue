<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2tu_cbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z2tu_cbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ruble-sign-solid" /></template>
