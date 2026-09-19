<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8_qo0hez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_qo0hez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:xmark-circle" /></template>
