<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrbxo8bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrbxo8bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pool" /></template>
