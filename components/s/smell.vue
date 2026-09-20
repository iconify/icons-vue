<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y81ss4bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y81ss4bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smell" /></template>
