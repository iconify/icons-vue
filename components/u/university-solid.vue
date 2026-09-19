<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypp5vkmzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypp5vkmzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:university-solid" /></template>
