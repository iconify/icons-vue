<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0q-nwe8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0q-nwe8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:order-checkbox-ascending" /></template>
