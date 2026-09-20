<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6tz7acsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6tz7acsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pdt" /></template>
