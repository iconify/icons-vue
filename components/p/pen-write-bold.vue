<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwtecabub.css';
import '../../css/m/mlafkbsqu.css';
import '../../css/z/z1k-5fi1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwtecabub"/><path class="mlafkbsqu"/><path class="z1k-5fi1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pen-write-bold" /></template>
