<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5---93ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v5---93ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:power-virtual-server-disaster-recovery-automation" /></template>
