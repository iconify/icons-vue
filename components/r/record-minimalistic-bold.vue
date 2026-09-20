<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upuz4ypky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upuz4ypky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-bold" /></template>
