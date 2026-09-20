<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjrt05b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjrt05b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella-outline" /></template>
