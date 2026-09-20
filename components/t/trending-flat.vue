<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhl8kcbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhl8kcbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trending-flat" /></template>
