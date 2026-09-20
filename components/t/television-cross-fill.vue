<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slqnaebhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slqnaebhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:television-cross-fill" /></template>
