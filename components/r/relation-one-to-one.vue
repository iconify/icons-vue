<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqgoybcgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqgoybcgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-to-one" /></template>
