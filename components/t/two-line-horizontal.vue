<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s66ne_bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s66ne_bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:two-line-horizontal" /></template>
