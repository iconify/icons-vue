<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djj33lbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djj33lbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:page-up-solid" /></template>
