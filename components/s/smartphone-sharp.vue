<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxio1l9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlxio1l9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:smartphone-sharp" /></template>
