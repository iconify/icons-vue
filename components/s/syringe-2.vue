<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddbtrpxcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddbtrpxcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:syringe-2" /></template>
