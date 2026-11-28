<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxq6cbcbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxq6cbcbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sim-card-lock" /></template>
