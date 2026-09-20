<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1w0zbc1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1w0zbc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:squares" /></template>
