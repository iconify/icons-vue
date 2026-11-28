<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhq0xobbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhq0xobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pins" /></template>
