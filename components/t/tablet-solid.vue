<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmmn-vnbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmmn-vnbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tablet-solid" /></template>
