<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ech9kbb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ech9kbb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:oura-o" /></template>
