<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i213nw56b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i213nw56b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-6-circle" /></template>
