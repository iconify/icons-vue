<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u560i_b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u560i_b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:receive-yens" /></template>
