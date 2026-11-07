<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb0xcujan.css';
import '../../css/u/uxqwpab0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb0xcujan"/><path class="uxqwpab0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-bold" /></template>
