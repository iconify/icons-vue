<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqw3ozb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqw3ozb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-axis-horizontal" /></template>
