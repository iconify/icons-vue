<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt0i_6v5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0i_6v5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stadium-star" /></template>
