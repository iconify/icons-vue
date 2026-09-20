<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7gk634bm.css';
import '../../css/t/t95fy_bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q7gk634bm"/><path class="t95fy_bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wifi-full-solid" /></template>
