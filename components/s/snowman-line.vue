<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqq5pvpql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqq5pvpql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowman-line" /></template>
