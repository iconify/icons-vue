<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkaa0nbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkaa0nbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:super-intelligence-speech" /></template>
