<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq733hbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="vq733hbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rains" /></template>
