<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5yg6700j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5yg6700j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-right-bold" /></template>
