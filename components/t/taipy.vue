<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgq2g6byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgq2g6byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:taipy" /></template>
