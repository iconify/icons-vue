<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdz4gjb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdz4gjb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nordic-walking" /></template>
