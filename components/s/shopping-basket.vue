<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi1_j4h9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="gi1_j4h9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-basket" /></template>
