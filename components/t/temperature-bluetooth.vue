<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krrf1_05m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krrf1_05m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature-bluetooth" /></template>
