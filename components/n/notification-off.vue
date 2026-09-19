<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4rrqlkh.css';
import '../../css/h/h68a5vtzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4rrqlkh"/><circle class="h68a5vtzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:notification-off" /></template>
