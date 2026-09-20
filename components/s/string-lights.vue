<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcnf5106n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcnf5106n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:string-lights" /></template>
