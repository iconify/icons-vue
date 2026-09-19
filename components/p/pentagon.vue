<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saw8iqbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saw8iqbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pentagon" /></template>
