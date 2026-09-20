<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woe70abka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woe70abka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-left-filled" /></template>
