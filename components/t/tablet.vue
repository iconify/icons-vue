<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve-xeub_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve-xeub_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tablet" /></template>
