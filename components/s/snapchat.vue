<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_j_82nop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_j_82nop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:snapchat" /></template>
