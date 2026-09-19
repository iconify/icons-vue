<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtkpeesbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtkpeesbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-half-filled" /></template>
