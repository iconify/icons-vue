<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh62hwbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh62hwbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:tag-alt" /></template>
