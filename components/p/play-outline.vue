<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub_n76btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub_n76btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-outline" /></template>
