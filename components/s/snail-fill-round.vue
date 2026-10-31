<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we8g2n_pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we8g2n_pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snail-fill-round" /></template>
