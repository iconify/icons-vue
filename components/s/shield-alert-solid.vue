<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq_xh8equ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq_xh8equ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-alert-solid" /></template>
