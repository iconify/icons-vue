<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcjsmgb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcjsmgb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-vertical2" /></template>
