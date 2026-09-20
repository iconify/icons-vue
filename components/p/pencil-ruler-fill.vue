<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua24uccfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua24uccfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ruler-fill" /></template>
