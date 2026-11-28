<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlnsih4bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlnsih4bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-right-split-solid" /></template>
