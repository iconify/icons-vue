<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slafz4i6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="slafz4i6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:stackpath" /></template>
