<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u05psrofy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u05psrofy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:panorama-horizontal-filled" /></template>
