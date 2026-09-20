<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjlkou6ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjlkou6ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-horizontal" /></template>
