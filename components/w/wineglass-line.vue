<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_78p0pql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_78p0pql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wineglass-line" /></template>
