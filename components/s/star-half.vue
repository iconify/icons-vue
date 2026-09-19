<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd6uv7bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd6uv7bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-half" /></template>
