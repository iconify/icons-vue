<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-bskn5pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-bskn5pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:piano-fill" /></template>
