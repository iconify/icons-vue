<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq4ba_b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq4ba_b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tv-2-fill" /></template>
