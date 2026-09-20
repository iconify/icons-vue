<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnp-2vbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnp-2vbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-night" /></template>
