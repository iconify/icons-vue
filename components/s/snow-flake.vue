<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4dft0rcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4dft0rcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:snow-flake" /></template>
