<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk4mz_b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk4mz_b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-source-initiative" /></template>
