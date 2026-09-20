<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrmfy3bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrmfy3bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:x-add" /></template>
