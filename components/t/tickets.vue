<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhjhcebay.css';
import '../../css/s/sq8m2mg-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhjhcebay"/><path class="sq8m2mg-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tickets" /></template>
