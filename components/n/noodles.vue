<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dle1xgb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dle1xgb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:noodles" /></template>
