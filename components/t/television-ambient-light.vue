<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxfgj3bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfgj3bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:television-ambient-light" /></template>
