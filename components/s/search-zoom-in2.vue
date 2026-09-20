<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1tvi29qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1tvi29qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-zoom-in2" /></template>
