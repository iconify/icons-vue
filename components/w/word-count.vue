<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2qr42b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2qr42b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:word-count" /></template>
