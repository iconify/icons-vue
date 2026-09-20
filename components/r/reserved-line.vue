<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7fs368qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7fs368qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reserved-line" /></template>
