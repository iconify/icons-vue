<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-pc_6xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iy-pc_6xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-grid-1x2" /></template>
