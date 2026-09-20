<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1h25rbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1h25rbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-paused-outline" /></template>
