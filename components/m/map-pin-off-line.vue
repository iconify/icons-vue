<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nox5ngbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nox5ngbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-off-line" /></template>
