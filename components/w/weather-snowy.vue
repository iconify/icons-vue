<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkugwpoxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkugwpoxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-snowy" /></template>
