<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ren2jybrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ren2jybrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:temp-sensor" /></template>
