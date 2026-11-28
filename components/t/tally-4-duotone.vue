<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zahzeybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zahzeybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-4-duotone" /></template>
