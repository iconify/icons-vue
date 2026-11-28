<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfrynbb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfrynbb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:server-refresh" /></template>
