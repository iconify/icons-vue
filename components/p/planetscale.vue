<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib9b4hbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib9b4hbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:planetscale" /></template>
