<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71k1pg1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w71k1pg1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pickaxe" /></template>
