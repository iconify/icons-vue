<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4a6h4vee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4a6h4vee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-down-solid" /></template>
