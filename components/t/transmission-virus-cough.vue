<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2sz3fbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2sz3fbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-cough" /></template>
