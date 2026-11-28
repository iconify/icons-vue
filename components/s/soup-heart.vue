<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck0xh6b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck0xh6b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:soup-heart" /></template>
