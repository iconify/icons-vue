<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjf5_gk6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjf5_gk6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pail-minus" /></template>
