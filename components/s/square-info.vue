<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m231y5u4n.css';
import '../../css/c/cfsdedcbv.css';
import '../../css/e/e8un-zbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m231y5u4n"/><path class="cfsdedcbv"/><circle class="e8un-zbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-info" /></template>
