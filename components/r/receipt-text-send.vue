<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfk4ssalg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfk4ssalg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-send" /></template>
