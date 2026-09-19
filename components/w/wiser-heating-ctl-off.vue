<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj7tpabbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj7tpabbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wiser-heating-ctl-off" /></template>
