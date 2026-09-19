<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozhku5idx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozhku5idx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag" /></template>
