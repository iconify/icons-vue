<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsfusrboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfusrboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-eight-circle" /></template>
