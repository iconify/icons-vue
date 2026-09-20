<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgekp4wny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kgekp4wny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:thermometer" /></template>
