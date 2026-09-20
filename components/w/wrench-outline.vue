<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxn-5736a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxn-5736a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrench-outline" /></template>
