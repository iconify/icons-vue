<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqce_m6so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqce_m6so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:microscope" /></template>
