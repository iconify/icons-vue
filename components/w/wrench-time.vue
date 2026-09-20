<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct25gz22c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct25gz22c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrench-time" /></template>
