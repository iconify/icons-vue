<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq5z0w1nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq5z0w1nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper-minus-outline" /></template>
