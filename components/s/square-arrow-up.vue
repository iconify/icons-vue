<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxskyzbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxskyzbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-arrow-up" /></template>
