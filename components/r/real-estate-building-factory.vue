<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t02gsl99c.css';
import '../../css/i/ipce-91ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t02gsl99c"/><path class="ipce-91ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-factory" /></template>
