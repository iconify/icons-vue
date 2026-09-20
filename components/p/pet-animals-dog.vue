<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o98vbdcga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o98vbdcga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-dog" /></template>
