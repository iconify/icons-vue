<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwu8b083h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwu8b083h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring-alarm-panel" /></template>
