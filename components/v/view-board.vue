<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj1qj2dgf.css';
import '../../css/x/xdvevhb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1qj2dgf"/><path class="xdvevhb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:view-board" /></template>
