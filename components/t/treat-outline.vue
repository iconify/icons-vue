<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryaepbcls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryaepbcls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:treat-outline" /></template>
