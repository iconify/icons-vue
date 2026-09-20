<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp_z5zbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp_z5zbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:reciept-alt" /></template>
