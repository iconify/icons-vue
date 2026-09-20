<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a40icebkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a40icebkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smartphone-text" /></template>
