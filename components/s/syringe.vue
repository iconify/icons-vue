<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd8ib77jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd8ib77jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:syringe" /></template>
