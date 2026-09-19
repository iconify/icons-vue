<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu0ey4b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu0ey4b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ruler-arrows" /></template>
