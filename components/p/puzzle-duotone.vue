<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ez_g0zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q1ez_g0zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-duotone" /></template>
