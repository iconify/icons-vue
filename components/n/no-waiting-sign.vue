<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krz0u-imm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krz0u-imm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:no-waiting-sign" /></template>
