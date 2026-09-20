<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq6mhac5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq6mhac5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ram-2-fill" /></template>
