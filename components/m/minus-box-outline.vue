<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2s7v_ssu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2s7v_ssu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:minus-box-outline" /></template>
