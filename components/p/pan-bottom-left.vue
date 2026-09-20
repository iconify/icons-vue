<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w51dps7dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w51dps7dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-bottom-left" /></template>
