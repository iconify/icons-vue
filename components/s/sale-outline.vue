<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvzlr703x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvzlr703x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sale-outline" /></template>
