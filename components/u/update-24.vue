<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps8b1zbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps8b1zbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:update-24" /></template>
