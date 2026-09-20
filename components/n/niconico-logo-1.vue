<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xevyw136x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xevyw136x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:niconico-logo-1" /></template>
