<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oof5z-bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oof5z-bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shovel" /></template>
