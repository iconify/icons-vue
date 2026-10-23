<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp6mnbcdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6mnbcdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pilcrow-right" /></template>
