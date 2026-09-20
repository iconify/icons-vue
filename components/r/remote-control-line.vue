<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spwubs0vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spwubs0vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:remote-control-line" /></template>
