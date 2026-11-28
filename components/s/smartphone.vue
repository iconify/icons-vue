<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt-_zab-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt-_zab-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone" /></template>
