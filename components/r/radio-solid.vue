<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibo_w4bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibo_w4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:radio-solid" /></template>
