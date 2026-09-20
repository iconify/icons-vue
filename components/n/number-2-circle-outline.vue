<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_d5dbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_d5dbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-2-circle-outline" /></template>
