<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af-ztgbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af-ztgbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:presentation" /></template>
