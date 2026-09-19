<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9h6a3mpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="z9h6a3mpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:opencart" /></template>
