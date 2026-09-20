<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7m2cdbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7m2cdbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-orbit" /></template>
