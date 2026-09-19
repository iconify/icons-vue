<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjwijzwhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjwijzwhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-floorlamp" /></template>
