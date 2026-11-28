<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-b4eiupb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-b4eiupb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:subscript-solid" /></template>
