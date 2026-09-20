<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7_4w1gdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7_4w1gdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-vibrate" /></template>
