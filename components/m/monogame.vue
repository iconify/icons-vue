<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk8l4sozy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk8l4sozy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monogame" /></template>
