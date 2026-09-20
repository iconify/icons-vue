<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sljpikbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sljpikbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-circle-outline" /></template>
