<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-7uwvhns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-7uwvhns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vuejs" /></template>
