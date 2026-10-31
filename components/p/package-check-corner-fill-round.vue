<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_m7_hhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_m7_hhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-check-corner-fill-round" /></template>
