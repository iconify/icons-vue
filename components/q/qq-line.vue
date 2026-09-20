<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u265_o_gg.css';
import '../../css/f/fwtgwcf6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u265_o_gg"/><path class="fwtgwcf6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qq-line" /></template>
