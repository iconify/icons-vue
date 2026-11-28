<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inuaq7k-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inuaq7k-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-3" /></template>
