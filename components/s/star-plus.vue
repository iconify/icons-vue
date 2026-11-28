<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrr1f-bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrr1f-bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:star-plus" /></template>
