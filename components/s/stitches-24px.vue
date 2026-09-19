<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9qmeobvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9qmeobvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stitches-24px" /></template>
