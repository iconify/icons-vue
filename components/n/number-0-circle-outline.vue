<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy_hb70yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy_hb70yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-0-circle-outline" /></template>
