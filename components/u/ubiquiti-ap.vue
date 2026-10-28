<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g09n5j3dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g09n5j3dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-ap" /></template>
