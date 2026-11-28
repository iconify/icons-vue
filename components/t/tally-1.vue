<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1a2m1m3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1a2m1m3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-1" /></template>
