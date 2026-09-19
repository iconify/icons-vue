<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wel5m5zih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wel5m5zih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:volume-min" /></template>
