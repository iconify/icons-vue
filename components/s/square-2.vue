<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8e7qdjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq8e7qdjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-2" /></template>
