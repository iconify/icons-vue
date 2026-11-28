<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtar19kwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtar19kwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:monitor-off" /></template>
