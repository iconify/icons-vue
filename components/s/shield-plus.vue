<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnowupb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnowupb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-plus" /></template>
