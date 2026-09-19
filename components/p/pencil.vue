<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz966bb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz966bb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pencil" /></template>
