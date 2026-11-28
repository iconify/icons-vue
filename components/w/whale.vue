<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu3-06lbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu3-06lbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:whale" /></template>
