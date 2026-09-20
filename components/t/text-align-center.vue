<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyi9b4b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyi9b4b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-align-center" /></template>
