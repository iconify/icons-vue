<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtz05xbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtz05xbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-basket-1" /></template>
