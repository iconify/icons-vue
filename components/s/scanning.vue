<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ema3nk49z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ema3nk49z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scanning" /></template>
