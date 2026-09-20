<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5x66vqgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5x66vqgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-right" /></template>
