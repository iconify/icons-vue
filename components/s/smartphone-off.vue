<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0bo2fi3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0bo2fi3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone-off" /></template>
