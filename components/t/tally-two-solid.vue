<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so4zo0bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so4zo0bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-two-solid" /></template>
