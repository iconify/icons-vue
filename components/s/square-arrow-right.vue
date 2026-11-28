<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os59_phhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os59_phhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-arrow-right" /></template>
