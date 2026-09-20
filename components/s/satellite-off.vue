<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4h48gfgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4h48gfgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:satellite-off" /></template>
