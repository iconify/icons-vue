<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_iisjog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6_iisjog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-6-circle-outline" /></template>
