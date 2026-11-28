<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqw20ubea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqw20ubea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:reply" /></template>
