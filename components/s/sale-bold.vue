<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trzro9bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="trzro9bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sale-bold" /></template>
