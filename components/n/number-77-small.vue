<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhogzpbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhogzpbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-77-small" /></template>
