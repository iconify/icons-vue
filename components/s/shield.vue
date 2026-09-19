<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnilibc4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnilibc4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:shield" /></template>
