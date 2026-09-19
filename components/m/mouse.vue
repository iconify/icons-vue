<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnh6lfzed.css';
import '../../css/w/wax2jmrhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnh6lfzed"/><path class="wax2jmrhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:mouse" /></template>
