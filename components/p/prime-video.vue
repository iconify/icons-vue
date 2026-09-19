<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w038znbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w038znbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prime-video" /></template>
