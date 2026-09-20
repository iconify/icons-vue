<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmnc5x6pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmnc5x6pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:union-solid" /></template>
