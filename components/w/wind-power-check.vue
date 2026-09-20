<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anhh36llh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anhh36llh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wind-power-check" /></template>
