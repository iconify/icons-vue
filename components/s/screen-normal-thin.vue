<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1x9vb-ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1x9vb-ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-normal-thin" /></template>
