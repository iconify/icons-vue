<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl5ivb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfl5ivb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:receipt" /></template>
