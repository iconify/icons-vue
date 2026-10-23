<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_n4mbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_n4mbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-align-justify-end" /></template>
