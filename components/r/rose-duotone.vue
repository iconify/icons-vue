<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ws80bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w1ws80bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rose-duotone" /></template>
