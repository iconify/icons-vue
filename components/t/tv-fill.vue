<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiu2e4bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiu2e4bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tv-fill" /></template>
