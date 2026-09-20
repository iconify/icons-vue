<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itjmgykbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="itjmgykbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:universe" /></template>
