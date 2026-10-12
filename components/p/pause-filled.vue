<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa5195bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa5195bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pause-filled" /></template>
