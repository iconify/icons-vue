<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyjspsb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="fyjspsb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:table-2" /></template>
