<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlb75okwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlb75okwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seat-legroom-reduced" /></template>
