<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nicg6-4io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nicg6-4io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spade-solid" /></template>
