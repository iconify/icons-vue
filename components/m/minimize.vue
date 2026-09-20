<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_p988bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_p988bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:minimize" /></template>
