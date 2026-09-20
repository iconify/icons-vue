<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shdx1tgjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shdx1tgjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:undo-line" /></template>
