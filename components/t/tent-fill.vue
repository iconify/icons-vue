<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guwnbjdbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guwnbjdbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tent-fill" /></template>
