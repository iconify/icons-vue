<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po6afib6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po6afib6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mushroom" /></template>
