<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw_-oib3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_-oib3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:server-off" /></template>
