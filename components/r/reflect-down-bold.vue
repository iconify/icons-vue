<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk6a7rbpz.css';
import '../../css/y/ya8a87bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6a7rbpz"/><path class="ya8a87bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:reflect-down-bold" /></template>
