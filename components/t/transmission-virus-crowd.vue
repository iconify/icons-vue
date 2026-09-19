<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toko7hbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toko7hbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-crowd" /></template>
