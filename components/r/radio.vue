<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgc7bi6_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgc7bi6_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:radio" /></template>
