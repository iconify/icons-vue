<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf1ugp_oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf1ugp_oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mayan-pyramid" /></template>
