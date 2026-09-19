<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nus_c7byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nus_c7byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:opencart" /></template>
