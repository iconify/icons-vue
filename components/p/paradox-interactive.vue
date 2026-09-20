<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnl4as1cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnl4as1cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:paradox-interactive" /></template>
