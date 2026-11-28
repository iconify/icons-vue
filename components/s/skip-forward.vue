<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ev_2bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ev_2bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:skip-forward" /></template>
