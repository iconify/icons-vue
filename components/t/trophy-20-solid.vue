<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyheg1bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oyheg1bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trophy-20-solid" /></template>
