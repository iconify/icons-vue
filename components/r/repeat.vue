<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnhlx4bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnhlx4bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:repeat" /></template>
