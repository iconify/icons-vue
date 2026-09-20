<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy32accpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy32accpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-remove" /></template>
