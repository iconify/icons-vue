<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsziz-bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsziz-bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-5-fill" /></template>
