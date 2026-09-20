<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntrjd3bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntrjd3bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-minus-outline" /></template>
