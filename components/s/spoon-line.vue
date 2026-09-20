<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uor33c4rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uor33c4rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spoon-line" /></template>
