<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6-zcrkji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6-zcrkji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-05" /></template>
