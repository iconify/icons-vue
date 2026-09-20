<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4zqb_bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4zqb_bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-4" /></template>
