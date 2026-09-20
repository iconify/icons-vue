<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuhumb8sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuhumb8sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-6-box-multiple" /></template>
