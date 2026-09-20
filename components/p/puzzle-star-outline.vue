<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvmp6ybyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvmp6ybyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-star-outline" /></template>
