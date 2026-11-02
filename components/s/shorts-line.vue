<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9nh_bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9nh_bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shorts-line" /></template>
