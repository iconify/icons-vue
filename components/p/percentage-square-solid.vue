<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_lsb4blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_lsb4blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-square-solid" /></template>
