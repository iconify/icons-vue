<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slhz6db9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slhz6db9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rewind-solid" /></template>
