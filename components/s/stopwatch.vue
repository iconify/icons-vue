<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms3tv4bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3tv4bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:stopwatch" /></template>
