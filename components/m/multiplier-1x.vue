<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_rljcbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_rljcbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:multiplier-1x" /></template>
