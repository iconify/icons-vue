<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8cx_kbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m8cx_kbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-partly-cloudy" /></template>
