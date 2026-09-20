<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy0q25fis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0q25fis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ted-logo-bold" /></template>
