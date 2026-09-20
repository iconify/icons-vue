<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fywckbc3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fywckbc3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:unfold-more-horizontal" /></template>
