<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9f9qcklb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9f9qcklb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sun-solid" /></template>
