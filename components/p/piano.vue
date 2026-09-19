<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzt8clmuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzt8clmuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:piano" /></template>
