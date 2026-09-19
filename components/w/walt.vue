<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa-a72udx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa-a72udx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:walt" /></template>
