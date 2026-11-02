<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwm26vjmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwm26vjmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-3-fill" /></template>
