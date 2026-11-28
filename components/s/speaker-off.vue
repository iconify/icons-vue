<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih012-wpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih012-wpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker-off" /></template>
