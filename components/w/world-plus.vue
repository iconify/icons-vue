<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tih9fbbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tih9fbbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:world-plus" /></template>
