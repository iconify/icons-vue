<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5w1t-bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5w1t-bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:train-check" /></template>
