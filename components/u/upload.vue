<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-7bhxbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-7bhxbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:upload" /></template>
