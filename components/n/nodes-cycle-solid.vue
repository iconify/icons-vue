<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooogucbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooogucbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:nodes-cycle-solid" /></template>
