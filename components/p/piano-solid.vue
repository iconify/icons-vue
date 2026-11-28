<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfbk5nxgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfbk5nxgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:piano-solid" /></template>
