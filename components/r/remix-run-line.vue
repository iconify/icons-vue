<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmobyc_fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmobyc_fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remix-run-line" /></template>
