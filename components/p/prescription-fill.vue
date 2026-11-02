<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmd_l1_lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmd_l1_lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:prescription-fill" /></template>
